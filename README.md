# Character-Level RNN for Text Generation

"This project implements a character-level recurrent neural network (RNN) using PyTorch to generate text. The model learns from a given sequence of text and generates new text one character at a time."

Features:
  - Defines a character-level RNN with:
      - An embedding layer to convert characters to dense vectors.
      - A single-layer RNN with 128 hidden units.
      - A fully connected layer to map RNN outputs to the vocabulary size.
  - Trains the model using CrossEntropyLoss and Adam optimizer.
  - Generates text by predicting the next character based on a given seed text.
