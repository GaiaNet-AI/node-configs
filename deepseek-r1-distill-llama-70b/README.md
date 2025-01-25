# A Deepseek R1 Distilled node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/deepseek-r1-distill-llama-70b/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/getting-started/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

> If the server fails to start, it is probably due to low memory on your device. You can edit the `config.json` file and reduce the `chat_ctx_size` field to `4096`, and start it again.

## References

* [Gaia node quick start guide](https://docs.gaianet.ai/getting-started/quick-start)
* [LlamaEdge LLM getting started guide](https://llamaedge.com/docs/user-guide/llm/full-openai)
* [LlamaEdge introduction](https://llamaedge.com/docs/user-guide/)
* [Gaia GitHub](https://github.com/GaiaNet-AI/gaianet-node)
* [LlamaEdge GitHub](https://github.com/LlamaEdge/LlamaEdge)
