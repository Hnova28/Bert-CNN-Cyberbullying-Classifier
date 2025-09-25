# 🚨 Cyberbullying Detection with BERT + CNN

## 📌 Overview
This project builds an **AI-powered cyberbullying detection model** that classifies online text into **6 categories**:  
- not_cyberbullying
- other cyberbullying
- gender  
- religion  
- age  
- ethnicity  

The model combines **BERT embeddings** with a **CNN classifier**, achieving **93% accuracy** on the test set.

---

## 🎯 Business Motivation
Cyberbullying is a critical challenge for online communities.  
This solution can be applied to:  
- 🛡️ Protect users from online harassment  
- 📊 Provide actionable insights into abusive behavior  
- 🤖 Power moderation tools for platforms  

---

## 🛠️ Tech Stack
- Python 3  
- TensorFlow & Keras  
- Hugging Face Transformers (BERT)  
- Scikit-learn  
- Matplotlib & Seaborn  

---

## 📂 Dataset
- Filtered dataset with 6 classes.  
- Train/test split: **90/10**.  
- Labels encoded numerically for training.  

---

## 🤖 Model Architecture
1. **BERT (bert-base-uncased)** → contextual embeddings  
2. **CNN layers** → feature extraction  
3. **Global Max Pooling** → dimensionality reduction  
4. **Dense + Softmax** → multi-class classification  

---

## 📊 Results

**Classification Report**

| Class              | Precision | Recall | F1-Score |
|---------------------|-----------|--------|----------|
| not_cyberbullying   | 0.83      | 0.89   | 0.86     |
| gender              | 0.92      | 0.91   | 0.92     |
| religion            | 0.95      | 0.93   | 0.94     |
| age                 | 0.98      | 0.97   | 0.98     |
| ethnicity           | 0.99      | 0.97   | 0.98     |

✅ **Overall Accuracy:** 93%  

---

## 📈 Visualizations
- Confusion Matrix  
- Accuracy & Loss curves  

---
## 💼 Business Value
- Social Media Platforms → real-time moderation
- EdTech Tools → safe digital classrooms
- Corporate Tools → inclusive communication monitoring
- Research & NGOs → analyze online abuse patterns
----
## 📌 In future can be done the next steps

- API deployment (FastAPI/Flask)
- Multilingual dataset support
- Advanced fine-tuning (BERT + hybrid models)

