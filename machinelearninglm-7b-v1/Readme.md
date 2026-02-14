# MachineLearningLM-7B-v1 Node

This configuration sets up a GaiaNet node to run `MachineLearningLM-7B-v1`, a powerful 7B parameter model fine-tuned for questions related to machine learning, data science, and other technical topics.

## Step 1: Install GaiaNet node

The GaiaNet node software version should be 0.5.4 or higher.

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

## Step 2: Init with the MachineLearningLM-7B-v1 model

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/machinelearninglm-7b-v1/config.json
```

## Step 3: Start the node

```bash
gaianet start
```

Now you can use the node as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* **Official Base Model:** [MachineLearningLM/MachineLearningLM-7B-v1](https://huggingface.co/MachineLearningLM/MachineLearningLM-7B-v1)
* **GGUF Formatted Model:** [Tobivictor/MachineLearningLM-7B-v1-GGUF](https://huggingface.co/Tobivictor/MachineLearningLM-7B-v1-GGUF)
* **GaiaNet Node Quick Start Guide:** https://github.com/GaiaNet-AI/gaianet-node