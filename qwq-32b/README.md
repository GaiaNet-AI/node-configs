# A QWQ-32b node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the QWQ-32b model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwq-32b/config.json
```


**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/Qwen/QwQ-32B)
* [GGUF formatted model](https://huggingface.co/gaianet/QwQ-32B-GGUF/blob/main/QwQ-32B-Q5_K_M.gguf)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
