# TASK - 4 Spam Message Detection using Natural Language Processing (NLP)

## 📘 Objective
The objective of this project is to build a machine learning model capable of detecting **spam messages** from text data (SMS/email) using Natural Language Processing techniques.  
The model classifies incoming messages as either **Spam** or **Ham (Not Spam)**.

---

## 🧩 Steps Performed

### 1. **Data Loading**
- Loaded the dataset (`spam.csv`) using `pandas`.
- Inspected the dataset structure, missing values, and distribution of spam vs ham messages.

### 2. **Data Preprocessing**
- Removed irrelevant columns and handled null values.
- Converted all text to lowercase for uniformity.
- Removed **punctuations, stopwords**, and **special characters**.
- Applied **tokenization** and **stemming** using NLTK’s `PorterStemmer`.
- Cleaned text data stored in a new processed column.

### 3. **Exploratory Data Analysis (EDA)**
- Analyzed message length, word count, and frequency distribution.
- Created **WordClouds** to visualize the most common words in spam and ham messages.
- Used **Seaborn** and **Matplotlib** for visual insights into the dataset.

### 4. **Feature Extraction**
- Transformed text into numerical form using:
  - **Bag of Words (CountVectorizer)**
  - **TF-IDF Vectorizer**
- Encoded target labels using `LabelEncoder`.

### 5. **Model Training**
- Split data into training and testing sets using `train_test_split`.
- Trained models such as:
  - **Naive Bayes**
  - **Logistic Regression**
  - **Support Vector Machine (SVM)**
- Evaluated each model using accuracy and confusion matrix.

### 6. **Model Evaluation**
- Calculated key metrics:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1 Score**
- Displayed **confusion matrix** to assess model performance.
- Identified the most effective classifier for spam detection.

---

## ⚙️ Tools & Libraries Used
| Category | Tools/Libraries |
|-----------|----------------|
| Data Handling | `pandas`, `numpy` |
| NLP Processing | `nltk`, `string`, `collections`, `wordcloud` |
| Visualization | `matplotlib`, `seaborn` |
| Feature Extraction | `CountVectorizer`, `TfidfVectorizer` |
| Machine Learning | `scikit-learn` (Naive Bayes, SVM, Logistic Regression) |

---

## 🏁 Outcome
- Built a text classification model capable of identifying spam messages with high accuracy.
- **Naive Bayes** performed the best with excellent precision and recall.
- Generated visualizations (WordClouds) highlighting the most frequent spam and ham keywords.
- Successfully demonstrated an end-to-end NLP pipeline — from raw text cleaning to model deployment.

---


