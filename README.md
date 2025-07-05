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

---

## 🧩 Technologies Used

- Python 3.x  
- Scikit-learn (TF-IDF, ML models)  
- NLTK (Text Preprocessing)  
- Hugging Face Transformers (for advanced model)  
- Gradio (Interactive web interface)  

---

## ⚙️ How to Run

### 1. Install Requirements

```bash
pip install -r requirements.txt
````

For Transformer support:

```bash
pip install transformers torch
```

---

### 2. Launch the Gradio Interface

```bash
python sentiment_analyzer.py
```

The Gradio web app will open automatically. You can also share the app via a public link.

---

## 🕹️ Features in the Web App

### ✅ Model Training

* Choose Sample Data or upload your custom dataset (CSV)
* Train using:

  * Traditional ML (TF-IDF + SVM)
  * Transformer-based (RoBERTa, no training required)
* View performance metrics (Accuracy, Precision, Recall, F1-Score)

### ✅ Text Analysis

* Enter text to analyze sentiment
* Displays prediction, confidence score, and probability breakdown

### ✅ File Analysis

* Upload a `.txt` file (one sentence/review per line)
* Provides sentiment breakdown for the entire file

---

## 📁 Project Structure

```
Advanced-Sentiment-Analyzer/
├── sentiment_analyzer.py      # Main Python script for sentiment analysis
└── sentiment_analyzer.ipynb   # Jupyter Notebook version
```


---

## 👨‍💻 Author

Developed by **B Akash Krishna**
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

