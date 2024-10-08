# 🐍 Guide to Running the BERT Model Training Script

This file provides instructions for running the script that trains a BERT model using PyTorch and the Transformers library.

## 📋 Requirements

Ensure you have the following libraries installed: **pandas**, **scikit-learn**, **torch**, and **transformers**. You can install these libraries using `pip`. For example, open your command prompt or terminal and type:

```bash
pip install pandas scikit-learn torch transformers
```

## 📁 Necessary Files

Make sure you have the following CSV files in the `data/` directory:

- `df_custom_v1_1.csv`
- `df_kaggle_v1_0.csv`
- `df_combined.csv`

These files should contain two columns: 'statement' and 'status'.

## 🚀 How to Run the Script

1. Open a terminal or command prompt.
2. Navigate to the directory where your `bert_trainer.py` file is located.
3. Execute the script by typing the following command:

```bash
python bert_trainer.py
```
The script will train three different BERT models using the provided datasets and save the trained models and metrics in the models/ folder.
