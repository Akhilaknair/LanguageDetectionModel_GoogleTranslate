# 🌐 Language Detection using Multinomial Naive Bayes Model

This project is a simple but effective **Language Detection System** built with Python using the **Multinomial Naive Bayes** algorithm. It identifies the language of a given text input from among 22 supported languages.

## 📂 Dataset

The dataset used is a multilingual text dataset with 1000 samples per language for a total of 22 languages.

Each sample in the dataset includes:
- `Text`: A sentence or phrase in one of the languages.
- `Language`: The corresponding language label.



## 🧪 Tech Stack

- Python 🐍
- Pandas & NumPy
- Scikit-learn (`CountVectorizer`, `MultinomialNB`, `train_test_split`)



## 🚀 How It Works

1. **Data Loading & Cleaning**: Reads a CSV file `language.csv` and checks for missing values.
2. **Text Vectorization**: Converts text into numerical features using `CountVectorizer`.
3. **Train-Test Split**: Splits the data into training (67%) and testing (33%) subsets.
4. **Model Training**: Trains a `MultinomialNB` model on the training data.
5. **Accuracy**: The model achieves **~95.3%** accuracy on the test set.
6. **User Input**: Takes a user input string and predicts the language.



## 🧠 Model Performance

- **Algorithm**: Multinomial Naive Bayes
- **Accuracy**: ~95.31%


