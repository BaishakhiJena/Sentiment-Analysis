# 🎬 Sentiment Analysis using Naive Bayes

A simple Machine Learning project that predicts whether the sentiment of a user-provided text is **Positive** or **Negative**.

The model is trained using the **NLTK Movie Reviews** dataset and built with **Python**, **NLTK**, and **Scikit-learn**.

---

## ✨ Features

* 📝 Predicts the sentiment of custom text
* 🤖 Uses the **Multinomial Naive Bayes** algorithm
* 📊 Converts text into numerical features using **CountVectorizer**
* 📈 Displays model accuracy and a classification report
* 💻 Interactive command-line interface

---

## 🛠️ Tech Stack

* Python
* NLTK
* Pandas
* Scikit-learn

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/BaishakhiJena/Sentiment-Analysis.git
cd sentiment-analysis
```

### 2. Install the dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the project

```bash
python sentiment_analysis.py
```

> **Note:** The `movie_reviews` dataset is downloaded automatically the first time you run the program.

---

## 💡 Example

**Input**

```text
Enter any text: I absolutely loved this movie!
```

**Output**

```text
Predicted Sentiment: Positive😊
```

**Input**

```text
Enter any text: The movie was okay, nothing special.
```

**Output**

```text
Predicted Sentiment: Negative😞
```

---

## 📌 Notes

* The model accepts any text as input.
* Since it is trained on the **NLTK Movie Reviews** dataset, it performs best on movie review–style text.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.
