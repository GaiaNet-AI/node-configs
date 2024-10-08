# A Llama-3.1-8B node with Rust language docs

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Llama-3.1-8B model and [Rust books](https://www.rust-lang.org/learn)

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/llama-3.1-8b-instruct_rustlang/config.json
```

> Use the `config.fullcontext.json` file in `init` to start a node with the full 128k context window if your machine has sufficient memory.

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.
