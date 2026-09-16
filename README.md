# make_your_own_RAG
Recently, Retrieval-Augmented Generation (RAG) has emerged as a powerful paradigm in the field of AI and Large Language Models (LLMs). RAG combines information retrieval with text generation to enhance language models' performance by incorporating external knowledge sources. source https://huggingface.co/blog/ngxson/make-your-own-rag
## Download ollama and models
First, let's start by installing ollama from project's website: ollama.com

After installed, open a terminal and run the following command to download the required models:

```bash
ollama pull hf.co/CompendiumLabs/bge-base-en-v1.5-gguf
ollama pull hf.co/bartowski/Llama-3.2-1B-Instruct-GGUF
```
If you see the following output, it means the models are successfully downloaded:

```
pulling manifest
...
verifying sha256 digest
writing manifest
success
```

Before continuing, to use ollama in python, let's also install the ollama package:
```bash
pip install ollama
```