# A stablelm-2-zephyr-1.6b node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Llama-3-8B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/stablelm-2-zephyr-1.6b/config.json
```


**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/stabilityai/stablelm-2-zephyr-1_6b)
* [GGUF formatted model](https://huggingface.co/gaianet/stablelm-2-zephyr-1.6b-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)





