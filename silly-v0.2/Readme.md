# silly-v0.2 Node

This configuration sets up a GaiaNet node to run `silly-v0.2`, a highly capable fine-tuned model designed for creative, conversational, and role-playing interactions.

## Step 1: Install GaiaNet node

The GaiaNet node software version should be 0.5.4 or higher.

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

## Step 2: Init with the silly-v0.2 model

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/silly-v0.2/config.json
```

## Step 3: Start the node

```bash
gaianet start
```

Now you can use the node as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* **Official Base Model:** [wave-on-discord/silly-v0.2](https://huggingface.co/wave-on-discord/silly-v0.2)
* **GGUF Formatted Model:** [Tobivictor/silly-v0.2-GGUF](https://huggingface.co/Tobivictor/silly-v0.2-GGUF)
* **GaiaNet Node Quick Start Guide:** https://github.com/GaiaNet-AI/gaianet-node