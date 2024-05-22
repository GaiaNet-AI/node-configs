# A Phi-3-mini-128k node 

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://raw.githubusercontent.com/GaiaNet-AI/gaianet-node/main/install.sh' | bash
```

Step 1a: For now, you need to install a preview version of [WasmEdge](https://github.com/WasmEdge/WasmEdge) in order to support the new Phi-3 models

```
curl -sSf https://raw.githubusercontent.com/WasmEdge/WasmEdge/master/utils/install_v2.sh | bash -s -- --ggmlbn=b2963
```

**Step 2:** Init with the Phi-3-mini-128k model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/phi-3-mini-instruct-128k/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/microsoft/Phi-3-mini-128k-instruct)
* [GGUF formatted model](https://huggingface.co/gaianet/Phi-3-mini-128k-instruct-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
