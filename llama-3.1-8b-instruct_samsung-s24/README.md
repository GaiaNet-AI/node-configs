# A Llama-3.1-8B node with Base chain docs

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Llama-3.1-8B model and [Samsung Galaxy S24 user guide](https://www.galaxys24manual.com/wp-content/uploads/pdf/galaxy-s24-manual-SAM-S921-S926-S928-OS14-011824-FINAL-US-English.pdf)

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/llama-3.1-8b-instruct_samsung-s24/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

