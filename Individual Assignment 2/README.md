# Stress Detection in Reddit Posts

## Overview
This project builds and evaluates multiple models (Structured Features, TF-IDF, DistilBERT) to classify Reddit posts as Stressed vs Non-Stressed using the Dreaddit dataset.

## Models Implemented
- Structured Logistic Regression (LIWC + linguistic features)
- TF-IDF + Logistic Regression
- DistilBERT (fine-tuned)

## Key Results
| Model      | Test F1 |
| ---------- | ------- |
| Structured | 0.756   |
| TF-IDF     | 0.740   |
| DistilBERT | 0.82    |

## Setup Instructions

### 1. Clone repository
git clone git@github.com:zhixin-lim/DSA4262.git

cd DSA4262

cd "Individual Assignment 2"

### 2. Create virtual environment
python3.11 -m venv venv

source venv/bin/activate   # Mac/Linux

### 3. Install dependencies
(pip install --upgrade pip)

pip install -r requirements.txt

### 4. Run notebook
jupyter notebook

Then open: 
DSA4262 Individual Assignment 2.ipynb

Note: 
Recommended Python version: 3.10 or 3.11

