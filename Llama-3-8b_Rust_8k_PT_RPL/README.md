# Llama-3-8B with a Paris tour guide

  

 Install GaiaNet node

  

```

curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

```

  
  ## Base Model: [Llama-3-8b-Instruct-4bit](https://huggingface.co/unsloth/llama-3-8b-Instruct-bnb-4bit)
  ## Fine Tuning dataset: [Huggingface Link](https://huggingface.co/datasets/Ak1104/combined_dataset_rust)
 - This dataset is has been used to fintune this model 
 - It focuses on improving model response for Rust queries.

## RAG implementation: [snapshot](https://huggingface.co/Ak1104/snapshot/blob/main/rpl1_book.snapshot.tar.gz) 

 - This snapshot is created from [Rust programing Language book](https://doc.rust-lang.org/book/#the-rust-programming-language)


## References

  

* [Official PyTorch model](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct)

* [GGUF formatted model](https://huggingface.co/gaianet/Llama-3-8B-Instruct-GGUF)

* [Knowledge vector collection](https://huggingface.co/datasets/gaianet/paris)

* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)