# 🚀 Toxicity Evasion Attack Detection Using Adversarially Robust Deep Learning Models

## 📌 Overview
This project focuses on detecting toxic and harmful content in online platforms using **robust deep learning techniques**. It addresses the limitations of traditional toxicity detection systems by incorporating **multimodal learning (text + image)** and improving resistance to **adversarial evasion attacks**.

The proposed system introduces a novel architecture called **U-EARDNet (Unified Evasion-Aware Robust Detection Network)** that enhances the reliability of automated content moderation systems.

---

## 🎯 Problem Statement
Most existing toxicity detection systems:
- Focus only on **text-based analysis**
- Fail to handle **multimodal data (memes, images + text)**
- Are vulnerable to **evasion attacks** (misspellings, symbol replacements, semantic changes)

This project solves these issues by building a **robust multimodal toxicity detection system**.

---

## 🧠 Proposed Solution
The project proposes a **multimodal deep learning framework** that:
- Uses **DistilBERT** for text understanding
- Uses **ResNet18** for image feature extraction
- Combines both using a **gated feature fusion mechanism**

👉 Final Model: **U-EARDNet**

---

## 🏗️ System Architecture
The system follows these steps:

1. Data Collection (Jigsaw + Hateful Memes dataset)
2. Data Preprocessing (text cleaning + image normalization)
3. Feature Extraction  
   - Text → DistilBERT  
   - Image → ResNet  
4. Multimodal Fusion (U-EARDNet)
5. Classification (Toxic / Non-Toxic)
6. Evaluation (Accuracy, Precision, Recall, F1)

---

## 📊 Datasets Used
- **Jigsaw Toxic Comment Dataset** (Text-based toxicity)
- **Facebook Hateful Memes Dataset** (Multimodal toxicity)

📌 *Note: Dataset is not included in this repository due to size.*

---

## ⚙️ Tech Stack
- Python  
- PyTorch  
- Transformers (Hugging Face)  
- Scikit-learn  
- NumPy, Pandas  
- OpenCV, PIL  
- Matplotlib, Seaborn  

---

## 🔬 Models Used
### 🔹 Baseline Models
- DistilBERT → Text classification  
- ResNet18 → Image classification  

### 🔹 Proposed Model
- **U-EARDNet**
  - Multimodal architecture
  - Gated feature fusion
  - Handles text, image, or both

---

## 🧪 Methodology
- Data preprocessing (normalization, tokenization)
- Binary toxicity classification
- Stratified train-validation split
- Feature extraction using deep learning models
- Evasion-aware training (text perturbations)
- Multi-task learning for robustness

---

## 📈 Performance
- Baseline models perform well individually  
- Multimodal model significantly improves results  

✅ **Final Accuracy: ~96–97%**

👉 The model shows strong robustness against adversarial attacks and improves real-world reliability.

---

## 📊 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

## 🔍 Key Features
- Multimodal learning (text + image)
- Adversarial robustness
- Deep learning-based architecture
- Real-world applicable content moderation system


---

## ⚠️ Note
- Dataset is not uploaded due to size limitations
- Download datasets from Kaggle:
  - https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge
  - https://www.kaggle.com/datasets/parthplc/facebook-hateful-meme-dataset

---

## 🚀 Future Improvements
- Real-time deployment system  
- Multilingual toxicity detection  
- Improved explainability  
- Optimization for low-resource environments  

---

## 👩‍💻 Author
**Savathallapalli Jasmine**  
