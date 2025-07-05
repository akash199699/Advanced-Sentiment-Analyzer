# 🎭 Advanced Sentiment Analyzer

An interactive, web-based Sentiment Analysis system that combines both **traditional machine learning** (TF-IDF + SVM) and **Transformer-based** approaches to classify text as Positive, Negative, or Neutral. Designed for flexibility, explainability, and ease of use.

---

## 🎯 Project Highlights

✅ Supports Traditional ML (TF-IDF + SVM, Random Forest, Logistic Regression)  
✅ Optional Transformer-based Sentiment Analysis (RoBERTa via Hugging Face)  
✅ Clean, Gradio-powered web interface  
✅ File batch processing for sentiment analysis  
✅ Confidence scores and probability distributions  
✅ Modular, extensible Python code  
✅ Google Colab notebook for easy testing  

---

## 🧩 Technologies Used

- Python 3.x  
- Scikit-learn (TF-IDF, ML models)  
- NLTK (Text Preprocessing)  
- Hugging Face Transformers (for advanced model)  
- Gradio (Interactive web interface)  
- Matplotlib, Seaborn (Optional visualizations)  

---

## ⚙️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/akash199699/Advanced-Sentiment-Analyzer.git
cd Advanced-Sentiment-Analyzer
````

---

### 2. Install Requirements

For Transformer support:

```bash
pip install transformers torch
```

---

### 3. Launch the Gradio Interface (Locally)

```bash
python sentiment_analyzer.py
```

OR run the Jupyter Notebook:

```bash
jupyter notebook sentiment_analyzer.ipynb
```

---

### 4. Run on Google Colab (No Setup Required)

Click below to open the notebook on Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)]((https://colab.research.google.com/drive/1HGtOZmL40Sj6qhxrhOKvIca1y2n-ZcA-?usp=sharing)](https://colab.research.google.com/drive/1r_MLV4IWSA6vyjM-5e_sB5mslGpWoueM?usp=sharing))

---

## 📂 Repository Structure

```
Advanced-Sentiment-Analyzer/
├── Review Data File for Uploading.txt   # Sample text file for file analysis
├── Custom Training Data.csv             # Sample CSV for custom model training
├── sentiment_analyzer.ipynb             # Jupyter Notebook version for experimentation
└── sentiment_analyzer.py                # Complete system with Gradio interface (Python script)
```

---

## 🕹️ Features in the Web App

### ✅ Model Training

* Train with Sample Data or upload your own CSV
* Choose between:

  * Traditional ML (TF-IDF + SVM)
  * Transformer-based (RoBERTa, no training required)
* View performance metrics (Accuracy, Precision, Recall, F1-Score)

### ✅ Text Analysis

* Enter text to analyze sentiment
* View prediction, confidence score, and probability breakdown

### ✅ File Analysis

* Upload a `.txt` file (one sentence/review per line)
* Provides sentiment breakdown and confidence scores

---

## 👨‍💻 Author

Developed by **Akash Krishna**
As part of an AI Internship by Novolo AI.

---

## 💡 Future Enhancements

* Deep Learning model fine-tuning
* Real-time API for external integration
* Advanced visualizations (confusion matrix, class distributions)
* Enhanced error handling and data validation

---

## 📝 License

This project is for educational and demonstration purposes. Feel free to use or extend it for personal projects.

```
