# A Mistral Small 24B node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/mistral-small-24b-instruct/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/getting-started/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

> The full context size of Mistral Small 24B is 32,768. You can edit the `config.json` file and increase the `chat_ctx_size` field to `32768`, and start it again if you have enough memory.

## References

* [Gaia node quick start guide](https://docs.gaianet.ai/getting-started/quick-start)
* [Gaia GitHub](https://github.com/GaiaNet-AI/gaianet-node)
* [LlamaEdge GitHub](https://github.com/LlamaEdge/LlamaEdge)
