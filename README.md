# Text Generation with RNN, LSTM and GRU

A learning project that trains three sequence models - a Vanilla RNN, an LSTM and a GRU - on the same text corpus and compares them side by side for next-word prediction and text generation.

Built to understand how sequence models learn grammar, sentence flow and long-term dependencies, and why gated architectures (LSTM, GRU) outperform a plain RNN.

## What the notebook does

1. Loads a small text corpus (easy to swap in your own - song lyrics, stories, PDF text)
2. Tokenizes the text and builds n-gram sequences for next-word prediction
3. Trains three models with the same setup:
   - Vanilla RNN (baseline - struggles with long-term dependencies)
   - LSTM (input/forget/output gates)
   - GRU (simpler, faster gated variant)
4. Compares training loss, generated text quality and how each handles longer contexts

## Run it

Open the notebook in Google Colab or Jupyter and run all cells. TensorFlow 2.x is the only real dependency:

```
pip install tensorflow numpy matplotlib
```

## Stack

Python, TensorFlow/Keras, NumPy, Matplotlib
