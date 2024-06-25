# Llama-3-8B with a Paris tour guide

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Llama-3-8B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/llama-3-8b-instruct_paris/config.json
```

Or, if you have at least 32GB of VRAM, you could use the full 8k context size of the model.

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/llama-3-8b-instruct_paris/config_full.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct)
* [GGUF formatted model](https://huggingface.co/gaianet/Llama-3-8B-Instruct-GGUF)
* [Knowledge vector collection](https://huggingface.co/datasets/gaianet/paris)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
