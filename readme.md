# Experiments with Mistral-7B-Instruct-v0.2 Quantized Models for Entity Extraction 

**Problem Statement**: From a text corpus, extracting entities dynamically is not possible with BERT-like models and inaccurate using GLiner etc. Using a quantized LLM can fill this requirement.

## In this Repo

- `mistraltest.ipynb` contains the code to load and experiment different quantized versions of mistral.

## Key Takeaways

- `llama-cpp` is used for optimized implementation of LLM inference.
- 

## Todo

- Currently inference running on CPU. Do it on GPU