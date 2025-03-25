# A EXAONE-3.5-2.4b node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the EXAONE-3.5-2.4b model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/exaone-3.5-2.4b-instruct/config.json
```


**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/LGAI-EXAONE/EXAONE-3.5-2.4B-Instruct)
* [GGUF formatted model](https://huggingface.co/gaianet/EXAONE-3.5-2.4B-Instruct-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
