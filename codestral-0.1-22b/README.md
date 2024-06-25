# A Codestral-0.1-22B node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Codestral-0.1-22B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/codestral-0.1-22b/config.json
```

Or, if you have at least 128GB of VRAM, you could use the full 32k context size of the model.

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/codestral-0.1-22b/config_full.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/mistralai/Codestral-22B-v0.1)
* [GGUF model](https://huggingface.co/gaianet/Codestral-22B-v0.1-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
