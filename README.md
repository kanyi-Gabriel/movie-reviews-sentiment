🎬 IMDB Sentiment Analysis  

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)  
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn&logoColor=white)  
![NLP](https://img.shields.io/badge/NLP-Text_Analysis-green?logo=apache-openoffice&logoColor=white)  
[![Kaggle Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue?logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)  

---

This project analyzes **50,000 IMDB movie reviews** to classify them as **positive** or **negative** using Natural Language Processing (NLP) techniques.  
It includes **data cleaning, exploratory analysis, feature engineering, and machine learning modeling**, demonstrating an end-to-end data science workflow.

---

##  Project Overview
- **Objective:** Build a sentiment classifier for IMDB reviews.  
- **Techniques Used:** Text preprocessing, TF-IDF vectorization, Logistic Regression, and model evaluation.  
- **Key Deliverables:**
  - Cleaned dataset with meaningful text
  - Visual insights into review patterns
  - Trained machine learning classifier
  - Evaluation with metrics and confusion matrix

---

## Repository Structure
```bash  
movie-reviews-sentiment/
│── README.md
│── requirements.txt
│── .gitignore
│
├── data/
│        └── IMDB_Dataset.zip        
│   
│
├── notebooks/           # Jupyter notebooks for analysis
│   └── sentiment.ipynb
│
├── LICENCE               
│
├── .gitattributes
│
└── reports/             
    └── summary_report.pdf
 ```
---


##  Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<kanyi-Gabriel>/movie-review-sentiment.git
   cd movie-review-sentiment-analysis
   
2. Create a virtual environment
    ```bash

   conda create -- name environment_name
   conda activate environment_name
   pip install -r requirements.txt
    
3. To add the environment to jupyter notebook
    ```bash
    conda install -c anaconda ipykernel
    python -m ipykernel install --user--name = environment_name
    ```
   ---
  ## Insights

