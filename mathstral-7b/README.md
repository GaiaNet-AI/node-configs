# A mathstral-7b node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the mathstral-7b model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/mathstral-7b/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/mistralai/mathstral-7B-v0.1)
* [GGUF model](https://huggingface.co/gaianet/mathstral-7B-v0.1-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
