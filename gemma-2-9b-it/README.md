# A Gemma-1.1-7B node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Gemma-2-9B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/gemma-2-9b-it/config.json
```

Or, if you have at least 32GB of VRAM, you could use the full 8k context size of the model.

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/gemma-2-9b-it/config_full.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/google/gemma-2-9b-it)
* [GGUF formatted model](https://huggingface.co/gaianet/gemma-2-9b-it-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
