# A finetuned node for Rust coding assistance

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the finetuned model and knowledge base

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/Llama-3-8b_Rust_8k_PT_RPL/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Finetuned model](https://huggingface.co/Ak1104/combined_dataset_rust/resolve/main/unsloth.Q4_K_M.gguf)
    * Base model is [Llama-3-8b-Instruct-4bit](https://huggingface.co/unsloth/llama-3-8b-Instruct-bnb-4bit)
    * Finetuned with [dataset of Rust QAs](https://huggingface.co/datasets/Ak1104/combined_dataset_rust)
* [Knowledge vector collection](https://huggingface.co/Ak1104/snapshot/blob/main/rpl1_book.snapshot.tar.gz) created from the [Rust programing Language](https://doc.rust-lang.org/book/#the-rust-programming-language) book
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
