# Yattas Tutorials — Notebooks

Companion Colab notebooks for tutorials at [yattas.com/tutorials](https://yattas.com/tutorials/). Each notebook runs independently under the reader's own Google account and Colab quota — nothing here is billed to or hosted by yattas.com.

## Core Math Review

Companion to the [Core Math Review](https://yattas.com/tutorials/core-math-review/) lesson: [core-math-review.ipynb](core-math-review.ipynb). Runs the same scalar/vector/dot-product/matrix examples as the lesson so the numbers are changeable, plus a small toy attention-score demo connecting the math to why transformers use it.

1. Scalars & Vectors
2. Dot Products: A Similarity Meter
3. Matrices: Machines That Rewrite Descriptions
4. Where This Shows Up: A Toy Attention Score

## Understanding Transformers — Build Your Own Transformer

Companion to the [Understanding Transformers](https://yattas.com/tutorials/transformers/) series: [build-your-own-transformer.ipynb](build-your-own-transformer.ipynb). The lessons teach concepts in the order that's easiest to *understand*; this notebook builds a transformer in the order you'd actually write one, section by section within a single continuous notebook so state (tokenizer, weights, trained model) carries forward naturally.

Runs on Colab's free CPU tier — nothing in this series needs a GPU.

1. Tokenization & Vocabulary
2. Embeddings & Positional Encoding
3. Self-Attention From Scratch
4. Multi-Head Attention
5. Feedforward, Residuals & LayerNorm
6. Assembling One Transformer Block
7. Stacking Blocks & the Output Head
8. Training Loop
9. Generation & Sampling
