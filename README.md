# Fine-tuned GPT-2 for Text Generation

This project demonstrates how to fine-tune a GPT-2 model on a custom text dataset (news articles) and use it for text generation. The notebook follows three main steps:

1. Data Preprocessing
2. Model Training
3. Model Inference

## Overview

The repository includes Python scripts that preprocess text data, fine-tune the GPT-2 model and generate text based on user input. 
The fine-tuned model can be used for text generation tasks such as continuing a given prompt or to create a summary of a news article.

## Requirements

- Python 3.7 or higher
- Transformers 4.47.x
- PyTorch (with CUDA support recommended)
- Pandas and NumPy for data manipulation

## Installation

Clone the repository:

```bash
git clone https://github.com/Patel4007/Fine_tuned_GPT2_project.git
```

Navigate to the repository and open the notebook

```bash
cd Fine_tuned_GPT2_project
jupyter notebook GPT2 fine tuned.ipynb
```

## Dataset

The dataset used for this project consists of news articles. The dataset is loaded from a CSV file (Articles.csv) and then preprocessed for training the GPT-2 model.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
