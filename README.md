# IMDb Sentiment Analysis - Portfolio Assignment 2

## Project Overview
This project focuses on **sentiment classification** of IMDb movie reviews using a **fine-tuned BERT model**. The goal is to classify reviews as **positive** or **negative** by leveraging **transfer learning** with the `bert-base-uncased` model from Hugging Face.

## Workflow
1. **Load IMDb Dataset** – Retrieve data from Hugging Face.
2. **Preprocessing** – Tokenize text using a transformer-based tokenizer.
3. **Model Fine-Tuning** – Train a BERT model on the dataset.
4. **Evaluation** – Assess performance using accuracy, F1-score, and confusion matrices.
5. **Deployment** – Deploy the model with Gradio for real-time user interaction.

## Repository Structure
- `notebooks/` - Jupyter/Colab notebooks for training and evaluation.
- `README.md` - Documentation and setup instructions.
- `models/` - Saved fine-tuned BERT models.
- `requirements.txt` - List of dependencies.

## Model Performance
- **Test Accuracy:** 88.8%
- **Test F1 Score:** 88.0%

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone 
   cd imdb-sentiment-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset & Citation
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



