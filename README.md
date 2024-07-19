# Text-generation-using-Markov-LSTM
Text generation using harry potter dataset on Markov and LSTM
# Harry Potter Text Generation

This project generates text inspired by the Harry Potter series using Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) networks. The model captures the unique style and language of the series.

## Features

- **Text Generation**: Mimics the Harry Potter writing style.
- **RNN & LSTM**: Handles sequential data and long-term dependencies.
- **Three-Layer Architecture**: Data preprocessing, LSTM units, and text generation.

## Requirements

- Python 
- PyTorch
- NumPy
- Pandas

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/vanibalani/Text-generation-using-Markov-LSTM/.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Train the Model**:
    ```python
    from train import train_model
    train_model(dataset_path='data/harry_potter.txt', epochs=50, batch_size=64)
    ```

2. **Generate Text**:
    ```python
    from generate import generate_text
    text = generate_text(model_path='models/lstm_model.h5', seed_text='Harry Potter and the')
    print(text)
    ```
