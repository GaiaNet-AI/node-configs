# jan-v1-2509 Node

This configuration sets up a GaiaNet node to run `jan-v1-2509`, a powerful instruction-tuned model.

## Step 1: Install GaiaNet node

The GaiaNet node software version should be 0.5.4 or higher.

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

## Step 2: Init with the jan-v1-2509 model

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/jan-v1-2509/config.json
```

## Step 3: Start the node

```bash
gaianet start
```

Now you can use the node as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* **Official Base Model:** [janhq/Jan-v1-2509](https://huggingface.co/janhq/Jan-v1-2509)
* **GGUF Formatted Model:** [Tobivictor/jan-v1-2509-GGUF](https://huggingface.co/Tobivictor/jan-v1-2509-GGUF)
* **GaiaNet Node Quick Start Guide:** https://github.com/GaiaNet-AI/gaianet-node