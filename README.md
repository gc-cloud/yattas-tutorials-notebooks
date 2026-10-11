# Yattas Tutorials: Notebooks

Companion Colab notebooks for tutorials at [yattas.com/tutorials](https://yattas.com/tutorials/). Each notebook runs independently under the reader's own Google account and Colab quota; yattas.com neither hosts nor bills for them.

## Core Math Review

Companion to the [Core Math Review](https://yattas.com/tutorials/core-math-review/) lesson: [core-math-review.ipynb](core-math-review.ipynb). Runs the same scalar/vector/dot-product/matrix examples as the lesson so the numbers are changeable, plus a toy attention-score demo showing where the math is used.

1. Scalars & Vectors
2. Dot Products: A Similarity Meter
3. Matrices: Machines That Rewrite Descriptions
4. Where This Shows Up: A Toy Attention Score

## Understanding Transformers: Build Your Own Transformer

Companion to the [Understanding Transformers](https://yattas.com/tutorials/transformers/) series: [build-your-own-transformer.ipynb](build-your-own-transformer.ipynb). The lessons teach concepts in the order that's easiest to *understand*; this notebook builds a transformer in the order you'd write one, in a single continuous notebook so the tokenizer, weights, and trained model carry forward.

Runs on Colab's free CPU tier; a GPU is optional.

1. Tokenization & Vocabulary
2. Embeddings & Positional Encoding
3. Self-Attention From Scratch
4. Multi-Head Attention
5. Feedforward, Residuals & LayerNorm
6. Assembling One Transformer Block
7. Stacking Blocks & the Output Head
8. Training Loop
9. Generation & Sampling
10. Speed, Autodiff, and Auto-Batching With JAX

## Agentic AI

Companion to the [Agentic AI](https://yattas.com/tutorials/agentic-ai/overview/) series: [agentic-ai.ipynb](agentic-ai.ipynb). Builds each part of an agent around Qwen2.5-3B-Instruct, a small open model that downloads and runs with no API key, in the order the lessons cover them. Plain Python first, so every part is visible; the last section rebuilds the same team of agents in LangGraph. Both versions have a chat loop you can use.

Runs on Colab's free CPU tier; a free GPU runtime speeds up generation and is worth enabling for Sections 7, 9, and 10, which make several model calls per question.

1. Loading a Small Open Model
2. A Calculator Tool, Called By Hand
3. The Reasoning Loop: Thought, Action, Observation
4. A Second Tool the Model Can't Know Without Asking
5. Multiple Tool Calls in One Question
6. Structured Tool Calling
7. Planning Before Acting
8. Memory and Context (transcript growth, compaction, long-term notes)
9. A Small Team of Agents (supervisor, specialists, audit log, chat loop)
10. The Same Team in LangGraph
