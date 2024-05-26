# A Yi-1.5-34B node with 16K context window

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://raw.githubusercontent.com/GaiaNet-AI/gaianet-node/main/install.sh' | bash
```

**Step 2:** Init with the Yi-1.5-34B-16K model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/yi-1.5-34b-chat-16k/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

> This model has a large (16k) context window and hence requires a large amount of RAM. If your machine is not able to start, you could try to reduce the `chat_ctx_size` field in `$HOME/gaianet/config.json` file to `8192`.

## References

* [Official PyTorch model](https://huggingface.co/01-ai/Yi-1.5-34B-Chat-16K)
* [GGUF formatted model](https://huggingface.co/gaianet/Yi-1.5-34B-Chat-16K-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
