# phi-3-mini-instruct-128k with a London tour guide

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the phi-3-mini-instruct-128k model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/phi-3-mini-instruct-128k_london/config.json
```

Or, if you have at least 64GB of VRAM, you could use the full 8k context size of the model.

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/phi-3-mini-instruct-128k_london/config_full.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

> This model has a large (128k) context window and hence requires a large amount of RAM. If your machine is not able to start, you could try to reduce the `chat_ctx_size` field in `$HOME/gaianet/config.json` file to `8192`.

## References

* [Official PyTorch model](https://huggingface.co/microsoft/Phi-3-mini-128k-instruct)
* [GGUF formatted model](https://huggingface.co/gaianet/Phi-3-mini-128k-instruct-GGUF)
* [Knowledge vector collection](https://huggingface.co/datasets/gaianet/london)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
