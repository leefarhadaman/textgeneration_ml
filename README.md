# Text Generation with Transformer Model

This project implements a Transformer-based text generation model using TensorFlow and Keras. It includes a simple GUI built with Tkinter for interactive text generation.

## Overview

The model is trained on a dataset of input and label text pairs. It uses a Transformer architecture with multi-head attention, positional encoding, and encoder-decoder layers. The GUI allows users to input text and receive generated responses from the model.

## Features

- Transformer model with custom layers (MultiHeadAttention, PositionalEncoding, Encoder, Decoder).
- Text preprocessing and vectorization using TensorFlow's `TextVectorization`.
- Interactive GUI for text input and response generation.
- Save and load model functionality.

## Requirements

- Python 3.x
- TensorFlow 2.x
- Tkinter (usually comes pre-installed with Python)
- NumPy
- Pandas

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/leefarhadaman/textgeneration_ml.git
   cd text-generation-transformer
   ```
2. Install the required packages:
  ```
  pip install -r requirements.txt
  ```
3. Download or prepare your dataset:
-- Place your input_texts.txt and label_texts.txt files in the input directory.
