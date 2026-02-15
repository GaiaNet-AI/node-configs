# Neeto-1.0-8b Node

This configuration sets up a GaiaNet node to run `Neeto-1.0-8b`, a versatile 8B parameter model fine-tuned for a wide range of instructional and conversational tasks.

## Step 1: Install GaiaNet node

The GaiaNet node software version should be 0.5.4 or higher.

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

## Step 2: Init with the Neeto-1.0-8b model

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/neeto-1.0-8b/config.json
```

## Step 3: Start the node

```bash
gaianet start
```

Now you can use the node as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* **Official Base Model:** [S4nfs/Neeto-1.0-8b](https://huggingface.co/S4nfs/Neeto-1.0-8b)
* **GGUF Formatted Model:** [Tobivictor/Neeto-1.0-8b-GGUF](https://huggingface.co/Tobivictor/Neeto-1.0-8b-GGUF)
* **GaiaNet Node Quick Start Guide:** https://github.com/GaiaNet-AI/gaianet-node