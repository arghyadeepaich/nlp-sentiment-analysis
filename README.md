

# 🧠 NLP Sentiment Analysis Project

This project demonstrates multiple approaches to **Sentiment Analysis** using both **classical NLP (NLTK)** and **modern transformer-based models (Hugging Face Transformers)**.
It provides insights into text sentiment polarity (positive, negative, neutral) using both methods and compares their performance.

---

## 🚀 Features

* Sentiment scoring using **NLTK VADER**
* Transformer-based sentiment analysis using **pretrained models (e.g., BERT, RoBERTa)**
* Text preprocessing with **stop word removal**
* Visualization of sentiment distributions with **Seaborn** and **Matplotlib**
* Easy integration for your own datasets

---

## 🧩 Tech Stack

* **Python 3.9+**
* **NLTK**
* **Transformers (Hugging Face)**
* **NumPy & Pandas**
* **Matplotlib & Seaborn**
* **SciPy**

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
```

### Example `requirements.txt`

```
nltk
transformers
numpy
pandas
matplotlib
seaborn
scipy
```

---

## 📘 Usage

Open the Jupyter notebook:

```bash
jupyter notebook "nlp_project (1).ipynb"
```

Or run the notebook in VSCode/JupyterLab to view results step by step.

---

## 📊 Workflow Overview

1. **Text Preprocessing**

   * Tokenization
   * Stopword removal
2. **VADER Sentiment Analysis**

   * Uses lexicon-based scoring from NLTK
3. **Transformer-Based Sentiment Analysis**

   * Uses a pretrained model (like `AutoModelForSequenceClassification`) from Hugging Face
   * Scores computed via softmax probabilities
4. **Visualization**

   * Compare sentiment distributions between the two approaches

---

## 📈 Results

* Classical and Transformer models give comparable trends on short text data.
* Transformers generally offer more nuanced contextual understanding.
* Visual plots summarize sentiment proportions across samples.

---

## 🧑‍💻 Author

**Arghyadeep Aich**
*Machine Learning & NLP Enthusiast*
📧 [[arghyadeepaich24@gmail](mailto:arghyadeepaich24@gmail)]
