# A Llama-3-8B node with 262K context window

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Llama-3-8B-262k model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/llama-3-8b-instruct-262k/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/gradientai/Llama-3-8B-Instruct-262k)
* GGUF formatted model: coming soon
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
