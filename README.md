 🚀 Spam Classification using DistilBERT  

## 📌 Project Overview  
This project implements a **spam classification model** using **DistilBERT**, a lightweight transformer model optimized for speed and performance. The goal is to classify messages as **spam** or **ham** (not spam) using **natural language processing (NLP)** techniques.  

## ✅ Features  
- **Fine-tunes DistilBERT** on a labeled spam dataset  
- **Tokenization & Text Preprocessing** with Hugging Face Transformers  
- **Model Training & Evaluation** using Precision, Recall, F1-score, and Confusion Matrix  
- **Optimized for Speed** compared to full BERT models  
  

## 📂 Dataset  
The dataset used contains **labeled spam messages** from various sources. It has two categories:  
- **Ham (0):** Non-spam messages  
- **Spam (1):** Spam messages  

## ⚙️ Tech Stack  
- **Python** 🐍  
- **Transformers (DistilBERT)**  
- **PyTorch**  
- **Scikit-learn**  
- **Pandas, Matplotlib**  

## 🏋️‍♂️ Model Training  
1. **Load & Preprocess Data**  
2. **Tokenize messages using `DistilBertTokenizer`**  
3. **Fine-tune `DistilBertModel` on spam dataset**  
4. **Optimize training with AdamW optimizer**  
5. **Evaluate performance using F1-score, Confusion Matrix**  

## 📊 Results  
- Achieved **high precision & recall** in spam detection  
- **Faster inference speed** compared to standard BERT models  
- Robust classification with minimal overfitting  
