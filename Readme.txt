# Simple Chatbot Using Machine Learning

## Overview
This project is a **simple ML-based chatbot** built using Python.  
The chatbot uses a small predefined set of intents, example user messages, and predefined responses.  
A **Logistic Regression classifier with TF-IDF features** is used to predict the most suitable intent for user input.

A Gradio interface is used to chat with the model interactively.

---

## How It Works
- Intents (tags, patterns, responses) are defined inside the notebook
- Text data is converted using **TfidfVectorizer**
- A **Logistic Regression model** is trained
- User input → predicted intent → one response is selected

This is a **rule-based ML chatbot**, not a generative AI model.

---

## Tech Stack
- Python  
- Google Colab / Jupyter Notebook

Libraries used:
- scikit-learn  
- nltk  
- random  
- gradio

---

## How to Run
1. Open `Simple_Chatbot_using_ML.ipynb`
2. Run all cells in order
3. Launch chatbot using Gradio
4. Start chatting in the UI

---

## Example
User: Hello  
Bot: Hi there!

---

## Usage Policy
- For learning & academic purposes only
- Responses are **predefined**
- Not suitable for real-world deployment

---

## Author
Manickavel Palani
