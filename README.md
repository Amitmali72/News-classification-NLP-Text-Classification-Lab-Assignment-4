# Lab Assignment 4: NLP - Text Classification

## 👨‍🎓 Student Details
- Name: Amit Ramchandra Mali  
- PRN: 202301070196  
- Batch: DL-3  

---

## 📌 Objective
The objective of this assignment is to implement Natural Language Processing (NLP) preprocessing techniques and build a text classification model using machine learning algorithms.

---

## 📊 Dataset
- Dataset Used: AG News Dataset  
- Description:  
  The dataset contains news articles categorized into four classes:
  - World  
  - Sports  
  - Business  
  - Sci/Tech  

Each record consists of a news title and description, which are combined to form the input text.

---

## ⚙️ Methodology

### 1. Data Preprocessing
The following preprocessing steps were applied:
- Conversion of text to lowercase  
- Removal of special characters and numbers  
- Tokenization  
- Stopword removal  
- Lemmatization  

---

### 2. Feature Extraction
- Text data was converted into numerical form using:
  - TF-IDF Vectorization  

---

### 3. Model Building
Two machine learning models were implemented:
- Naive Bayes (MultinomialNB)  
- Support Vector Machine (LinearSVC)  

---

### 4. Model Evaluation
The models were evaluated using:
- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

## 📈 Results

| Model | Accuracy |
|------|--------|
| Naive Bayes | 88.7% |
| SVM | 88.1% |

---

## 🧠 Conclusion
In this project, NLP preprocessing techniques were successfully applied to clean and prepare text data. TF-IDF vectorization was used to extract meaningful features from the text.

Among the implemented models, Naive Bayes performed slightly better than SVM, achieving an accuracy of 88.7%. This demonstrates that Naive Bayes is highly effective for text classification tasks, especially with high-dimensional sparse data.

Overall, the project highlights the importance of preprocessing and appropriate model selection in improving the performance of NLP systems.

---

## 🚀 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- NLTK  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📂 Repository Structure
- NLP_Text_Classification.ipynb → Main notebook  
- train.csv → Dataset file  
- README.md → Project documentation  
