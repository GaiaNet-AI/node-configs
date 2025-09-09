# Qwen2.5-Omni-7B Node

This configuration sets up a GaiaNet node to run the `Qwen2.5-Omni-7B` model, a powerful and versatile language model suitable for general chat and specialized tasks.

## Step 1: Install GaiaNet node

The GaiaNet node software version should be 0.5.4 or higher.

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

## Step 2: Init with the Qwen2.5-Omni-7B model

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2.5-omni-7b/config.json
```

## Step 3: Start the node

```bash
gaianet start
```

Now you can use the node as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* **Official Base Model:** [Qwen/Qwen2.5-Omni-7B](https://huggingface.co/Qwen/Qwen2.5-Omni-7B)
* **GGUF Formatted Model:** [Tobivictor/Qwen2.5-Omni-7B-GGUF](https://huggingface.co/Tobivictor/Qwen2.5-Omni-7B-GGUF)
* **GaiaNet Node Quick Start Guide:** https://github.com/GaiaNet-AI/gaianet-node