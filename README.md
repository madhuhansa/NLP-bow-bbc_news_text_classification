# BBC News Text Classification using Bag of Words

This project is a multi-class text classification task using the **BBC News Classification Dataset**. It uses the **Bag of Words (BoW)** model with **CountVectorizer** and **Multinomial Naive Bayes** classifier to classify news articles into categories like **business**, **entertainment**, **politics**, **sport**, and **tech**.

## 🔧 Technologies Used

- Python
- Scikit-learn
- spaCy
- Pandas, NumPy
- Jupyter Notebook

## 📁 Dataset

Dataset contains 2,225 articles from the BBC news website, labeled into 5 categories:
- business
- entertainment
- politics
- sport
- tech

Source: [Kaggle Dataset](https://www.kaggle.com/datasets/sunilthite/text-document-classification-dataset)

## 📊 Results

- Achieved **97% accuracy** on test data.
- Excellent classification performance across all categories.

## 📂 Folder Structure
```
bbc-news-text-classification-bow/
├── df_file.csv
├── df_filek.ipynb
└── README.md
```

## 📌 Future Improvements

- Try TF-IDF instead of BoW
- Use other models like SVM or Logistic Regression
- Visualize most frequent words per category

## 🙌 Credits

Dataset by Sunil Thite on Kaggle  
Developed by Yahan Madhuhansa
