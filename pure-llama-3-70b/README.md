# A Llama-3-70B node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://raw.githubusercontent.com/GaiaNet-AI/gaianet-node/main/install.sh' | bash
```

See the [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)

**Step 2:** Init with the Llama-3-70B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/pure-llama-3-70b/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/meta-llama/Meta-Llama-3-70B)
* GGUF formatted model: coming soon
