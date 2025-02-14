# IMDb Sentiment Analysis - Portfolio Assignment 2

## 📌 Project Overview
This repository contains the code, notebooks, and documentation for fine-tuning a **BERT-based sentiment classifier** on the **IMDb movie reviews dataset**. The goal of this project is to classify movie reviews as either **positive** or **negative** using **transfer learning** with the `bert-base-uncased` model from Hugging Face.

## 📂 Repository Structure
- `notebooks/` - Jupyter/Colab notebooks used for training and evaluation
- `README.md` - This file with project details and setup instructions

## 🔧 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/imdb-sentiment-classifier.git
   cd imdb-sentiment-classifier
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the IMDb dataset (if not using Hugging Face Datasets directly).

## 🚀 Running the Model
### 1️⃣ Training
Run the training script:
```bash
python scripts/train.py
```

### 2️⃣ Inference with Gradio
Run the interactive web app for prediction:
```bash
python scripts/app.py
```

## 📊 Model Performance
- **Test Accuracy:** 88.8%
- **Test F1 Score:** 88.0%

## 📜 Dataset & Citation
- **Dataset:** [IMDb Movie Reviews](https://huggingface.co/datasets/stanfordnlp/imdb)
- **Paper:** *Maas et al., "Learning Word Vectors for Sentiment Analysis", ACL 2011.*

```bibtex
@InProceedings{maas-EtAl:2011:ACL-HLT2011,
  author    = {Maas, Andrew L. and Daly, Raymond E. and Pham, Peter T. and Huang, Dan and Ng, Andrew Y. and Potts, Christopher},
  title     = {Learning Word Vectors for Sentiment Analysis},
  booktitle = {Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies},
  month     = {June},
  year      = {2011},
  address   = {Portland, Oregon, USA},
  publisher = {Association for Computational Linguistics},
  pages     = {142--150},
  url       = {http://www.aclweb.org/anthology/P11-1015}
}
```

