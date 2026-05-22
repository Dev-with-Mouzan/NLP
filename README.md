# Natural Language Processing Masterclass

<div align="center">

![NLP](https://img.shields.io/badge/NLP-Natural%20Language%20Processing-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.7+-brightgreen?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A comprehensive collection of interactive Jupyter notebooks covering fundamental to advanced concepts in Natural Language Processing (NLP).

</div>

---

## 📚 Table of Contents

- [Overview](#overview)
- [Course Modules](#course-modules)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Modules Description](#modules-description)
- [Contributing](#contributing)
- [License](#license)

---

## <span style="color:#0066cc">📖 Overview</span>

This repository is a complete learning resource for mastering Natural Language Processing. It covers the entire NLP pipeline from basic text preprocessing to advanced embedding techniques and model evaluation. Each module includes hands-on Jupyter notebooks with practical examples and explanations.

**What You'll Learn:**
- ✅ Core NLP concepts and fundamentals
- ✅ Text preprocessing and cleaning techniques
- ✅ Methods to convert text to numerical representations
- ✅ Feature engineering and N-gram models
- ✅ Modern embedding techniques (Word2Vec, Doc2Vec, USE)
- ✅ Subword tokenization and vocabulary handling
- ✅ Visualization and evaluation metrics

---

## 🎯 Course Modules

| # | Module | Status | Topics |
|---|--------|--------|--------|
| 01 | **What is NLP?** | ✅ | Introduction & Pipeline Creation |
| 02 | **Text Preprocessing** | ✅ | Cleaning, Stemming & Lemmatization |
| 03 | **Convert Text to Numbers** | ✅ | Bag of Words, Encoding, TF-IDF |
| 04 | **Feature Engineering & N-Grams** | ✅ | Feature Extraction Techniques |
| 05 | **Embeddings** | ✅ | Word2Vec, Doc2Vec, USE |
| 07 | **Tokenizers & SubWord Models** | ✅ | BPE, SentencePiece, WordPiece |
| 08 | **Visualization & Evaluation** | ✅ | Similarity, PCA, t-SNE, Sentiment Analysis |

---

## 📁 Project Structure

```
NLP/
├── README.md
├── 01-What_is_NLP/
│   ├── Intro.ipynb
│   └── Step_Creating_pipeline.ipynb
│
├── 02-Text_Preprocessing/
│   ├── Cleaning_text_pipeline.ipynb
│   ├── Stemming_lemmatization.ipynb
│   └── What_is_Text_preprocesing.ipynb
│
├── 03-Tech_to_convert_text_to_Num/
│   ├── BOW.ipynb
│   ├── Ingeger_Encoding.ipynb
│   ├── Technique_to_convert.ipynb
│   ├── TF_IDF_.ipynb
│   └── why_convert_text.ipynb
│
├── 04-Feature_Engineering_N-Gram/
│   ├── feature_engineering.ipynb
│   └── N-Gram.ipynb
│
├── 05-Embedding/
│   ├── Doc2vec_&_USE.ipynb
│   ├── pretrain_embedding_model.ipynb
│   ├── Sentecr_Document_Embedding.ipynb
│   ├── why_use_embedding.ipynb
│   └── Word2vec.ipynb
│
├── 07-Tokenizer_SubWord_Model/
│   ├── Out_of_Vacab.ipynb
│   ├── Vacab_Explosion.ipynb
│   ├── What_is_BPE.md
│   ├── What_is_Sentence_piece.ipynb
│   └── What_is_Wordpiece.ipynb
│
└── 08-Visualization_Evaluation/
    ├── Cosine_similarity.ipynb
    ├── PCA_vs_TSNE.ipynb
    ├── Sementic_neighborhood.ipynb
    └── Sentimental_Analysis.ipynb
```

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.7+**
- **Jupyter Notebook** or **JupyterLab**
- **pip** (Python package manager)

Required Python packages:
- `numpy` - Numerical computations
- `pandas` - Data manipulation
- `matplotlib` - Visualization
- `scikit-learn` - ML algorithms & evaluation
- `nltk` - Natural Language Toolkit
- `gensim` - Word embeddings (Word2Vec, Doc2Vec)
- `tensorflow` - Deep learning framework
- `scipy` - Scientific computing

### Installation

1. **Clone or download this repository:**
   ```bash
   git clone <repository-url>
   cd NLP
   ```

2. **Create a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required packages:**
   ```bash
   pip install jupyter numpy pandas matplotlib scikit-learn nltk gensim tensorflow scipy
   ```

4. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

5. **Open notebooks in your browser and start learning!**

---

## 💻 Usage

Each notebook is designed to be self-contained with:
- **Detailed explanations** of concepts
- **Code examples** demonstrating techniques
- **Visualizations** for better understanding
- **Practice exercises** for hands-on learning

**To run a notebook:**

1. Navigate to the desired module folder
2. Open the `.ipynb` file in Jupyter
3. Execute cells sequentially using `Shift + Enter`
4. Modify and experiment with the code to deepen understanding

---

## 📖 Modules Description

### 01 - What is NLP?
Get introduced to Natural Language Processing concepts and learn how to create an NLP pipeline from scratch.

**Topics:**
- Introduction to NLP
- NLP Pipeline creation

---

### 02 - Text Preprocessing
Master the essential techniques for cleaning and preparing text data.

**Topics:**
- Text cleaning pipelines
- Stemming and Lemmatization
- Text preprocessing fundamentals

---

### 03 - Converting Text to Numbers
Learn various methods to transform text into numerical representations.

**Topics:**
- Bag of Words (BoW)
- Integer Encoding
- TF-IDF
- Why convert text to numbers

---

### 04 - Feature Engineering & N-Grams
Understand feature extraction techniques and N-gram models.

**Topics:**
- Feature Engineering principles
- N-gram models
- Sequential feature extraction

---

### 05 - Embeddings
Explore modern word and document embedding techniques.

**Topics:**
- Word2Vec embeddings
- Doc2Vec embeddings
- Universal Sentence Encoder (USE)
- Pre-trained embedding models
- Why use embeddings

---

### 07 - Tokenizers & SubWord Models
Learn about advanced tokenization techniques and handling vocabulary challenges.

**Topics:**
- Byte Pair Encoding (BPE)
- SentencePiece tokenization
- WordPiece tokenization
- Vocabulary explosion handling
- Out-of-vocabulary (OOV) problems

---

### 08 - Visualization & Evaluation
Master techniques to visualize and evaluate NLP models.

**Topics:**
- Cosine similarity calculations
- PCA vs t-SNE visualization
- Semantic neighborhood analysis
- Sentiment analysis

---

## 🔧 Key Technologies

<table>
<tr>
<td align="center">
<a href="https://www.python.org/">
<img width="60" height="60" src="https://www.python.org/static/community_logos/python-logo.png" alt="Python"/>
<br/><b>Python</b>
</a>
</td>
<td align="center">
<a href="https://jupyter.org/">
<img width="60" height="60" src="https://jupyter.org/assets/logos/rectanglelogo-greytext-rgb.svg" alt="Jupyter"/>
<br/><b>Jupyter</b>
</a>
</td>
<td align="center">
<a href="https://scikit-learn.org/">
<img width="60" height="60" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" alt="Scikit-learn"/>
<br/><b>Scikit-learn</b>
</a>
</td>
<td align="center">
<a href="https://www.tensorflow.org/">
<img width="60" height="60" src="https://www.tensorflow.org/images/tf_logo_social.png" alt="TensorFlow"/>
<br/><b>TensorFlow</b>
</a>
</td>
</tr>
</table>

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues, feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 📬 Contact & Support

For questions, suggestions, or feedback:
- Open an issue in the repository
- Create a discussion thread
- Reach out via email

---

<div align="center">

**Happy Learning! 🎓**

Made with ❤️ for the NLP community

</div>
