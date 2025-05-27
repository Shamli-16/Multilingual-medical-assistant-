# Multilingual Medical Assistant

This project is an AI-powered assistant that predicts possible diseases based on symptoms entered in **multiple languages**. It uses **Google Translate API**, **LLMs**, and a trained **Machine Learning model** to analyze symptoms and provide predictions along with a pie chart visualization.

---

## Overview

- Accepts user symptoms in **any language**.
- Translates symptoms to **English** using **Google Translate API**.
- Uses a **trained ML model** (via TensorFlow) to predict the **top 3 diseases**.
- Visualizes the predicted disease percentages in a **pie chart** for easy understanding.

---

## Technologies Used

- **Languages & Libraries**: Python, Pandas, NumPy, Scikit-learn, Matplotlib
- **APIs**: Google Translate API
- **ML Techniques**: Classification models (KNN, Decision Tree), LLM (Transformer)
- **Environment**: Jupyter Notebook

---

## Dataset

The model is trained on a healthcare dataset that contains symptom-disease mappings with 170+ columns of medical symptoms.

---

## How It Works

1. **Input**: User enters symptoms in any language.
2. **Translation**: Google Translate API converts input to English.
3. **Prediction**: A trained model (using TensorFlow) predicts top diseases.
4. **Visualization**: The results are displayed with a pie chart showing disease likelihood.

---

## Why This Project is Important

- Promotes **early disease detection**, even for **non-English-speaking users**.
- Encourages the development of **accessible healthcare AI tools**.
- Can be expanded to integrate with **voice assistants**, **chatbots**, and **healthcare databases**.

---

## Author

**Samli Saloni Mohanty**  
B.Tech CSE (DS/ML)  
Siksha O Anusandhan (ITER)  
Email: samlimohanty16@gmail.com

---

## License

This project is intended for academic and educational purposes.
