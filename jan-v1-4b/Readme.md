# Jan-v1-4B Node

This configuration sets up a GaiaNet node to run the `Jan-v1-4B` model, a versatile and efficient model suitable for a wide range of conversational tasks.

## Step 1: Install GaiaNet node

The GaiaNet node software version should be 0.5.4 or higher.

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

## Step 2: Init with the Jan-v1-4B model

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/jan-v1-4b/config.json
```

## Step 3: Start the node

```bash
gaianet start
```

Now you can use the node as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* **Official Base Model:** [janhq/jan-v1-4b](https://huggingface.co/janhq/jan-v1-4b)
* **GGUF Formatted Model:** [Tobivictor/Jan-v1-4B-GGUF](https://huggingface.co/Tobivictor/Jan-v1-4B-GGUF)
* **GaiaNet Node Quick Start Guide:** https://github.com/GaiaNet-AI/gaianet-node