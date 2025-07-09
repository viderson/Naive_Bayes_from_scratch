# Naive Bayes from Scratch 📊🧠

This repository provides a complete implementation of the **Naive Bayes classifier from scratch** in Python. It is designed as an educational project to understand how probabilistic classifiers work internally, without relying on machine learning libraries like `scikit-learn`.

---

## 🔍 What is Naive Bayes?

Naive Bayes is a family of simple "probabilistic classifiers" based on applying Bayes' theorem with strong (naive) independence assumptions between features. It is widely used for:

- Text classification (e.g., spam detection)
- Sentiment analysis
- Medical diagnosis

---

## 📁 Project Structure

```
Naive_Bayes_from_scratch-main/
├── naive_bayes.py        # Core implementation of Naive Bayes
├── test.ipynb            # Jupyter notebook for testing and demo
├── data/                 # Sample datasets (optional)
└── README.md             # This file
```

---

## 🚀 How to Use

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/Naive_Bayes_from_scratch.git
cd Naive_Bayes_from_scratch
```

2. **Install dependencies**
```bash
pip install numpy pandas
```

3. **Run the notebook**
```bash
jupyter notebook test.ipynb
```

The notebook includes examples of training the Naive Bayes classifier, visualizing results, and evaluating performance.

---

## 🧠 Features of This Implementation

- Supports categorical and/or numerical features
- Manual computation of priors and likelihoods
- Log probabilities for numerical stability
- Clean class-based design

---

## 📚 Learning Goals

- Understand Bayes’ theorem and its use in classification
- Learn how independence assumptions simplify computations
- See real examples of applying probability to prediction

---

## 📜 License

This project is licensed under the MIT License.

---

## ✨ Author

Created with 💡 by [Your Name](https://github.com/yourusername)
