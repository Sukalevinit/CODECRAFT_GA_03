# Task 03 – Markov Chain Text Generation

## 📄 Project Description

This project implements a basic **Markov Chain** model to generate new text sequences. The model is built from sample text and uses word-based transitions to simulate coherent text generation. This is a foundational natural language processing (NLP) task focused on probabilistic modeling of language.

---

## 📦 Technologies and Libraries Used

* Python
* `random` (standard library)
* `collections.defaultdict`

---

## 🛠️ Setup Instructions

No external dependencies are needed. This project runs on any standard Python environment with no additional installation required.

Simply open and run the notebook: `Task03_CODECRAFT.ipynb`.

---

## 🚀 How It Works

1. **Input Text Initialization**
   A short sample paragraph is provided, which serves as the training data for building the Markov Chain.

2. **Tokenization**
   The paragraph is split into individual words.

3. **Transition Dictionary**
   A `defaultdict` is used to store a mapping of each word to the words that follow it, effectively building the Markov chain.

4. **Text Generation Function**
   A function named `generate_text()` is defined to generate new text based on:

   * A starting word
   * Desired output length

   It randomly chooses next words based on observed transitions from the original input text.

5. **Example Usage**
   A demonstration is included where the model generates a 20-word sentence starting from a selected word in the chain.

---

## 📈 Output

A sample output could look like this (based on randomness and structure of input):

```
Markov chains are a useful statistical tool. They can generate text by predicting the next word...
```

The output varies each time due to the use of `random.choice()` in the chain traversal.

---

## 📁 File Structure

```
Task03_CODECRAFT.ipynb   # Jupyter Notebook implementing the Markov chain text generator
```

---

## 🧠 Learning Outcome

By completing this task, you will:

* Understand the concept of Markov chains in NLP
* Learn how to tokenize and process text
* Implement a simple word-level text generator
* Practice working with dictionaries and random selection

---
