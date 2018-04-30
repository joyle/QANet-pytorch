# QANet-pytorch

# Introduction

An implementation of

## Usage

Python 3.6 & PyTorch 0.4

1. Install pytorch 0.4 for Python 3.6+
2. Run `pip install spacy tqdm ujson requests`
3. Run `python -m spacy download en`
4. Run `python main.py`

## Structure
dataset.py: download dataset and parse.

main.py: program entry.

models.py: QANet structure.

## Differences from the paper

1. The paper doesn't mention which activation function they used. I use relu.
2. I don't set the embedding of `<UNK>` trainable.
3.