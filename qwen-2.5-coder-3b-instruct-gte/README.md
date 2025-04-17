# A Qwen2.5-Coder-3B-gte node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Qwen2.5 Coder 3B LLM and GTE Qwen 2 1,5b embedding model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen-2.5-coder-3b-instruct-gte/config.json
```

**Step 3:** Start the node

```
gaianet start
```


