# 📝 Text Summarizer

**A Python-based application implementing both Extractive and Abstractive text summarization techniques.**  
Simplify your long texts with an intuitive and user-friendly interface built using **Streamlit**.

---

## 📜 Overview

The **Text Summarizer** application uses advanced natural language processing techniques to summarize large chunks of text into concise and meaningful content. Users can select between:  
- **Extractive Summarization**: Extracts key sentences from the input text using the **TF-IDF algorithm**.  
- **Abstractive Summarization**: Generates human-like summaries using HuggingFace’s **T5 Transformer model**.

---

## 🚀 Features

- 🔄 **Dual Summarization Modes**:  
  - **Extractive**: Highlights the most important sentences from the text.  
  - **Abstractive**: Creates entirely new sentences to summarize the content.  
- 💻 **Streamlit-based UI**: A clean, interactive interface for inputting and summarizing text.  
- 🖱️ **Easy-to-Use**: Simply paste your text, select the summarization type, and get the summary at the click of a button.

---

## 🛠️ Tech Stack

- **Programming Language**: Python 🐍  
- **Libraries and Tools**:  
  - `nltk`: Tokenization and stopword removal.  
  - `transformers`: HuggingFace's T5 model for abstractive summarization.  
  - `streamlit`: Intuitive UI for user interaction.  
- **Algorithms**:  
  - **TF-IDF**: For extractive summarization.  
  - **HuggingFace's T5-small Transformer**: For abstractive summarization.

---

## 🧠 How It Works

1. **Extractive Summarization**  
   - Tokenizes the text and computes word frequencies, ignoring stopwords and punctuation.  
   - Scores sentences based on the word frequencies.  
   - Selects the top sentences to generate a summary.

2. **Abstractive Summarization**  
   - Uses the HuggingFace **T5-small Transformer** model to understand and generate a concise version of the input text.  
   - Produces summaries that feel natural and coherent.
