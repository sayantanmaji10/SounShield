```markdown
# 🔊 Identification of Sounds from Construction Sites

### A Machine Learning Approach for Urban Sound Classification

An AI-based system designed to identify construction-site sounds in urban environments using **MFCC feature extraction** and **Random Forest classification**.

---

## 📌 Overview

Construction noise significantly affects health, productivity, and urban living quality.  
This project focuses on detecting construction-related sounds automatically to enable smart noise-monitoring and preventive systems.

The model was trained on **6000+ urban audio clips** containing both:

- Construction sounds
- Ambient urban sounds

---

## ⚙️ Tech Stack

- Python
- Machine Learning
- Random Forest
- MFCC (Mel Frequency Cepstral Coefficients)
- NumPy
- Matplotlib

---

## 🧠 Methodology

### Audio Processing
- Audio framing & Hanning Windowing
- MFCC-based feature extraction
- Multiple frame/window size experimentation

### Classification
Compared multiple ML models:

- Random Forest ✅
- SVM
- KNN
- Decision Tree
- Naive Bayes
- AdaBoost

---

## 📊 Results

✔ Achieved **98.02% accuracy**  
✔ Best performance with:
- 25-dimensional MFCC features
- 1280 sample window length
- Random Forest classifier

---

## 🌍 Applications

- Smart City Monitoring
- Noise Pollution Detection
- Hospital & School Safety
- Automated Noise-Control Systems

---

## 📄 Publication

Published in Springer:

🔗 https://link.springer.com/chapter/10.1007/978-981-97-5703-9_40

---

## 👨‍💻 Authors

- Sayantan Maji
- Himadri Mukherjee
- Ankita Dhar
- Matteo Marciano
- Kaushik Roy

---

> “Teaching machines to understand urban soundscapes.”
```
