# A Yi-1.5-9B node 

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Yi-1.5-9B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/yi-1.5-9b-chat/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.


## References

* [Official PyTorch model](https://huggingface.co/01-ai/Yi-1.5-9B-Chat)
* [GGUF formatted model](https://huggingface.co/gaianet/Yi-1.5-9B-Chat-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
