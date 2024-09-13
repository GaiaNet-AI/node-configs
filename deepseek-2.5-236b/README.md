# A Deepseek-2.5-236B node

**Prereq** Download the model file

```
curl -LO https://huggingface.co/bartowski/DeepSeek-V2.5-GGUF/resolve/main/DeepSeek-V2.5-Q4_0/DeepSeek-V2.5-Q4_0-00001-of-00004.gguf
curl -LO https://huggingface.co/bartowski/DeepSeek-V2.5-GGUF/resolve/main/DeepSeek-V2.5-Q4_0/DeepSeek-V2.5-Q4_0-00002-of-00004.gguf
curl -LO https://huggingface.co/bartowski/DeepSeek-V2.5-GGUF/resolve/main/DeepSeek-V2.5-Q4_0/DeepSeek-V2.5-Q4_0-00003-of-00004.gguf
curl -LO https://huggingface.co/bartowski/DeepSeek-V2.5-GGUF/resolve/main/DeepSeek-V2.5-Q4_0/DeepSeek-V2.5-Q4_0-00004-of-00004.gguf

cat DeepSeek-V2.5-Q4_0-00001-of-00004.gguf DeepSeek-V2.5-Q4_0-00002-of-00004.gguf DeepSeek-V2.5-Q4_0-00003-of-00004.gguf DeepSeek-V2.5-Q4_0-00004-of-00004.gguf > DeepSeek-V2.5-Q4_0.gguf
```

The Deepseek v2.5 is a large model. You can run the Q4 model with a 32k context window on a Mac Studio with 192GB RAM. If you 
have even large machines, you can use the full 128k context length in the `config.fullcontext.json` file.

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Deepseek-2.5-236B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/deepseek-2.5-236b/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

