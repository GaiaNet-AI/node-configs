# A GPT-OSS-20B node

**Step 1:** Install GaiaNet node

> The  Gaia node software version should be 0.5.4 or higher. 

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the GPT-OSS-20B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/gpt-oss-20b/config.json
```


**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/openai/gpt-oss-20b)
* GGUF formatted model: TBA
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
