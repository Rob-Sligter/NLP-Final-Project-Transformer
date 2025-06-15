## Transformer Translation Model
This repository contains a Transformer-based translation model implemented in PyTorch. The model is designed to translate text from French to English using a sequence-to-sequence architecture with attention mechanisms.

## Background
This Notebook was developed during the course Natual Language Processing at the University of Groningen.
This project was assesed with a 95/100.

## Requirements

- Python 3.9
- PyTorch 1.8.0
- Transformers 4.27.0
- Datasets 2.10.0
- NLTK 3.8.1
- NumPy <2
- ipywidgets
- Matplotlib

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. For GPU support (optional):
   ```bash
   pip install torch==1.8.0+cu111 -f https://download.pytorch.org/whl/torch_stable.html
   ```