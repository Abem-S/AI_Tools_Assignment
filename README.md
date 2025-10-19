# AI Tools Assignment

This repository contains my submission for the **AI Tools Assignment**, showcasing theoretical understanding, practical implementation, and ethical reflection using modern AI frameworks.

---

## 📂 Folder Structure

```
AI-Tools-Assignment/
│
├── Task1_ScikitLearn.ipynb        # Classical ML (Iris dataset using Decision Tree)
├── Task2_TensorFlow.ipynb         # Deep Learning (MNIST CNN model)
├── Task3_SpaCy.ipynb              # NLP (Named Entity Recognition + Sentiment)
│
└── aitool.pdf # Full report (theory, outputs, ethics)
```

---

## 🧠 Overview

This project explores three major areas of AI using popular frameworks:

### **Task 1: Classical ML with Scikit-learn**
- Built a **Decision Tree classifier** on the Iris dataset to predict flower species.
- Inspected and preprocessed the dataset.
- Split data into training and test sets (80/20).
- Evaluated using **accuracy, precision, and recall**.
- Achieved perfect classification, showing the effectiveness of decision trees on small structured datasets.

### **Task 2: Deep Learning with TensorFlow**
- Developed a **Convolutional Neural Network (CNN)** for handwritten digit recognition (MNIST dataset).
- Model includes convolutional layers, max pooling, flattening, and dense layers with softmax output.
- Normalized images and trained with **Adam optimizer** and **sparse categorical cross-entropy loss**.
- Achieved >95% test accuracy and visualized predictions on 5 sample images.

### **Task 3: NLP with spaCy**
- Performed **Named Entity Recognition (NER)** and **rule-based sentiment analysis** on Amazon product reviews.
- Extracted entities like product names and brands.
- Analyzed sentiment (positive/negative) using word-based rules.
- Demonstrated how NLP can extract insights from unstructured text.

---

## ⚖️ Ethics & Optimization

- **Potential Biases:**  
  - MNIST: Different handwriting styles or digit distributions could skew model accuracy.  
  - Amazon Reviews: Limited to English reviews and certain brands, potentially affecting sentiment results.  

- **Mitigation Strategies:**  
  - **TensorFlow Fairness Indicators:** Identify bias across subgroups (handwriting styles, digit types) and adjust training.  
  - **spaCy Rule-Based Checks:** Ensure consistent entity extraction and reduce mislabeling for uncommon brands.  

- **Troubleshooting Notes:**  
  - Common issues include shape mismatches and incorrect loss functions.  
  - Debugging involves checking tensor dimensions, loss function compatibility, and layer output shapes.

---

## ⚙️ Tools & Libraries

- **Frameworks:** TensorFlow, PyTorch, Scikit-learn, spaCy  
- **Environment:** Google Colab / Jupyter Notebook  
- **Language:** Python  
- **Datasets:** Iris Dataset, MNIST, Amazon Product Reviews  

---

## 🎥 Presentation Video

Watch the 3-minute project explanation video here:  
👉 [**AI Tools Assignment Presentation (Google Drive Link)**](https://drive.google.com/file/d/1OQiCBPaFrkJQ5NOLl3p-zyZEiDrqurVb/view?usp=sharing)

---

## 📄 PDF Report

The report (`aitool.pdf`) contains:  
- Answers to theoretical questions  
- Screenshots of model outputs for each task  
- Ethical reflection and troubleshooting notes  

---

## 🧩 Author

**Abemelek Samson Abduke**  

