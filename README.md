# Twitter US Airline Sentiment Analysis

This project analyzes the sentiment of tweets about U.S. airlines using the [Twitter US Airline Sentiment dataset](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) from Kaggle. The analysis covers data cleaning, exploratory data analysis, feature extraction, model training, and evaluation. 

## Table of Contents
- [Overview](#overview)
- [Data](#data)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [References](#references)
- [License](#license)

## Overview
The goal of this project is to classify tweets into sentiment categories (positive, negative, and neutral) using machine learning , NLP. The workflow includes:
- Data cleaning and preprocessing
- Feature engineering (e.g., TF-IDF)
- Model training with classifiers (e.g., Logistic Regression, Random Forest)
- Evaluation of model performance using common metrics

## Data
The dataset used is the "Twitter US Airline Sentiment" dataset available on Kaggle. It contains tweets, their sentiment labels, and additional metadata.  
- **Download Link:** [Kaggle Dataset](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)  
For more details on the dataset, refer to the Kaggle page.

## Methodology
- **Data Preprocessing:**  
  Clean the text data by removing noise (punctuation, stop words, etc.) and normalize the tweets.
- **Feature Engineering:**  
  Transform text data into numerical features using techniques like TF-IDF.
- **Modeling:**  
  Train machine learning models (e.g., Logistic Regression, Random Forest) on the processed data.
- **Evaluation:**  
  Evaluate the models using accuracy, precision, recall, and F1-score.
- **Visualization:**  
  Use libraries like Matplotlib and Seaborn to visualize sentiment distributions and model performance.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Naso7y/twitter-sentiment-analysis.git
   cd twitter-sentiment-analysis
   ```

2. **Set Up a Virtual Environment (Optional but Recommended):**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   The `requirements.txt` includes essential libraries such as:
   - [pandas](https://pandas.pydata.org/docs/)
   - [scikit-learn](https://scikit-learn.org/stable/documentation.html)
   - [spaCy](https://spacy.io/)
   - [matplotlib](https://matplotlib.org/stable/contents.html)
   - [seaborn](https://seaborn.pydata.org/)

4. **Download the Dataset:**
   Download the dataset from Kaggle and place the CSV file into the `data/` folder.

5. **Download spaCy Model:**
   ```bash
   python -m spacy download en_core_web_sm
   ```

## Usage

1. **Run the Analysis Notebook:**
   Navigate to the `notebooks/` directory and open the Jupyter Notebook:
   ```bash
   jupyter notebook Twitter_Sentiment_Analysis.ipynb
   ```
2. **Follow the Notebook Steps:**
   The notebook guides you through data preprocessing, model training, evaluation, and visualization.

## Project Structure
```
twitter-sentiment-analysis/
├── Twitter_Sentiment_Analysis.ipynb   # Jupyter Notebook for analysis
├── requirements.txt                         # List of required Python libraries
└── README.md
```

## References
- **Kaggle Dataset:** [Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)
- **pandas Documentation:** [pandas](https://pandas.pydata.org/docs/)
- **scikit-learn Documentation:** [scikit-learn](https://scikit-learn.org/stable/documentation.html)
- **spaCy Documentation:** [spaCy](https://spacy.io/)
- **Matplotlib Documentation:** [Matplotlib](https://matplotlib.org/stable/contents.html)


## 🤝 Contributions
I welcome all contributions! Feel free to fork the repository, submit issues, or create pull requests.

## 📬 Contact
For any questions or feedback, feel free to reach out:

- **GitHub:** [NASO7Y](https://github.com/NASO7Y)
- **Email:** ahmed.noshy2004@gmail.com
- **LinkedIn:** [Ahmed Noshy](https://www.linkedin.com/in/nos7y/)


---
⭐ If you find this project helpful, consider giving it a star is support😂🌹
