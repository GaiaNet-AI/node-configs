# Llama-4-Scout-17B-16E-Instruct-Q2_K node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/llama-4-scout-17b-16e-Instruct/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/getting-started/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

> The full context size of Llama-4-Scout-17B-16E-Instruct is 128k. You can edit the `config.json` file and increase the `chat_ctx_size` field to `131072`, and start it again if you have enough memory.

## References

* [Gaia node quick start guide](https://docs.gaianet.ai/getting-started/quick-start)
* [Gaia GitHub](https://github.com/GaiaNet-AI/gaianet-node)
* [LlamaEdge GitHub](https://github.com/LlamaEdge/LlamaEdge)
