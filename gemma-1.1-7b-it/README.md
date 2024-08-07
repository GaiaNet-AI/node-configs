# A Gemma-1.1-7B node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Gemma-1.1-7B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/gemma-1.1-7b-it/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/google/gemma-1.1-7b-it-GGUF)
* GGUF formatted model: coming soon
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
