# 🧑‍⚕️ Cancer Tumor Board Detection from HTML Pages  

## 📌 Project Overview  
This project aims to develop an automated method to detect tumor board discussions from webpages. Using **natural language processing (NLP)** and **keyword-based techniques**, we classify webpages into different confidence levels (no evidence, medium, high) and extract tumor board types (e.g., cancer types) and scheduling details. The model processes HTML pages to identify tumor board discussions and classify them accordingly.

## 🔍 Problem Statement  
In healthcare, tumor boards are critical meetings where medical professionals discuss cancer patients' cases. This project focuses on automatically identifying tumor board discussions from publicly available webpages, classifying the confidence level, and extracting key tumor board details such as tumor types and schedules.

## 🚀 Approach  

### 1️⃣ Data Preprocessing  
- Loaded the **train.csv** and **test.csv** files.  
- Processed **HTML pages** using BeautifulSoup to extract text content.  
- Applied **keyword-based matching** for tumor board detection.  
- Integrated **NLP techniques** to classify content and extract tumor board information.

### 2️⃣ Model Development  
- Developed a model using a combination of:
  ✅ **Keyword-based matching** to identify relevant content.  
  ✅ **Text classification** techniques to classify pages into confidence levels.  
  ✅ **Regular Expressions** for extracting tumor board schedules and types.  

### 3️⃣ Model Training & Optimization  
- **Loss Function:** Categorical Cross-Entropy  
- **Optimizer:** Adam  
- **Regularization:** Dropout to prevent overfitting  
- **Early Stopping:** Stops training when validation loss stops improving  

### 4️⃣ Evaluation Metrics  
- **Accuracy:** High accuracy in tumor board classification  
- **Precision & Recall:** Ensured high precision and recall across tumor board types  
- **Confusion Matrix & Classification Report** used for detailed analysis  

## 📊 Results  
✅ Achieved high accuracy in detecting tumor boards and classifying tumor types.  
✅ Successfully classified tumor board confidence levels: **No Evidence**, **Medium**, **High**.  
✅ Extracted **tumor board types** and **schedules** accurately.  
✅ Developed a **deployable model for tumor board detection and extraction**.  

## 💻 Installation  

### Prerequisites
- Python 3.7+
- Required libraries: 
  - `beautifulsoup4`
  - `pandas`
  - `scikit-learn`
  - `nltk`
  - `requests`

### Steps to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/nerohax/cancer-tumor-board-detection.git
   cd cancer-tumor-board-detection
