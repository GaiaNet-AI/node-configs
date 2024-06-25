# A Llama-2-7B node with Vitalik's knowledge

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the fine-tuned Llama-2-7B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/vitalik.eth-7b-chat_vitalik-blog/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [GGUF formatted model](https://huggingface.co/gaianet/vitalik.eth-7b)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
