# A Yi-Coder-9B-Chat node with a Rust knowledge base

**Step 1:** Install Gaia node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Yi-Coder-9b-Chat model with a Rust knowledge base

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/yi-coder-9b-chat_rustlang/config.json
```

> Use the `config.fullcontext.json` file in `init` to start a node with the full 128k context window if your machine has sufficient memory.

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Gaia node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
