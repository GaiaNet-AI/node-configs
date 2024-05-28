# A mistral-0.3-7b-instruct node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://raw.githubusercontent.com/GaiaNet-AI/gaianet-node/main/install.sh' | bash
```

**Step 2:** Init with the mistral-0.3-7b-instruct model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/mistral-0.3-7b-instruct/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

> This model has a large (32k) context window and hence requires a large amount of RAM. If your machine is not able to start, you could try the `config.lowmem.json` configuration, which reduces `chat_ctx_size` to `8192` and `embedding_ctx_size` to `512`.

## References

* [Official PyTorch model]()
* [GGUF formatted model]()
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
