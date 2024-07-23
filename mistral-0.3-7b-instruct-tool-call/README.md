# A mistral-0.3-7b-instruct node with tool call support

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the mistral-0.3-7b-instruct model and tool call prompt template

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/mistral-0.3-7b-instruct-tool-call/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model]()
* [GGUF formatted model]()
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
