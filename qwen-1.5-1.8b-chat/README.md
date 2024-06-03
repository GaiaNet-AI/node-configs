# A Qwen-1.5-1.8b-chat node 

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://raw.githubusercontent.com/GaiaNet-AI/gaianet-node/main/install.sh' | bash
```

**Step 2:** Init with the qwen-1.5-1.8b-chat model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen-1.5-1.8b-chat/config.json
```
Or, if you have at least 64GB of VRAM, you could use the full 32k context size of the model.

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen-1.5-1.8b-chat/config_full.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

> This model has a large (32k) context window and hence requires a large amount of RAM. If your machine is not able to start, you could try to reduce the `chat_ctx_size` field in `$HOME/gaianet/config.json` file to `8192`.

## References

* [Official PyTorch model](https://huggingface.co/Qwen/Qwen1.5-1.8B-Chat)
* [GGUF formatted model](https://huggingface.co/gaianet/Qwen1.5-1.8B-Chat-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
