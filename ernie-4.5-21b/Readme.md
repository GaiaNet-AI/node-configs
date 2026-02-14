# ERNIE-4.5-21B-A3B-Thinking Node

This configuration sets up a GaiaNet node to run `ERNIE-4.5-21B-A3B-Thinking`, a powerful large language model developed by Baidu, known for its advanced reasoning and conversational abilities.

## Step 1: Install GaiaNet node

The GaiaNet node software version should be 0.5.4 or higher.

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

## Step 2: Init with the ERNIE-4.5-21B-A3B-Thinking model

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/ernie-4.5-21b/config.json
```

## Step 3: Start the node

```bash
gaianet start
```

Now you can use the node as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* **Official Base Model:** [baidu/ERNIE-4.5-21B-A3B-Thinking](https://huggingface.co/baidu/ERNIE-4.5-21B-A3B-Thinking)
* **GGUF Formatted Model:** [Tobivictor/ERNIE-4.5-21B-A3B-Thinking-GGUF](https://huggingface.co/Tobivictor/ERNIE-4.5-21B-A3B-Thinking-GGUF)
* **GaiaNet Node Quick Start Guide:** https://github.com/GaiaNet-AI/gaianet-node