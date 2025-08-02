# 🎬 Movie Genre Classifier

Predicts the **genre** of a movie based on its **plot description** using **TF-IDF** and **Logistic Regression**.  
Built from scratch with **Python**, trained on a small dataset, and deployed using **Gradio**.

## 📌 Description

Movie Genre Classifier is a machine learning project that classifies movie genres based on plot summaries. It uses TF-IDF vectorization to process text and a logistic regression model to predict genres. The model achieves up to **95% accuracy** despite a small dataset of 100 movies.

## 🚀 Features
- 📖 Plot-to-genre prediction
- 🧠 TF-IDF vectorization + Logistic Regression
- 🎯 Accuracy up to 95%
- 🧪 Real-time testing with **Gradio UI**

## 🛠️ Technologies
- Python 3
- scikit-learn
- pandas
- Gradio

## 📈 Example

> Input: `"A young boy discovers he is a wizard and attends a magical school..."`  
> Output: `Fantasy`

## 🔧 How to Run

```bash
pip install -r requirements.txt
python main.py
