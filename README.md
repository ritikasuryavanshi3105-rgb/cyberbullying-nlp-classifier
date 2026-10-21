# Cyberbullying Text Classification Using NLP

## 📌 Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to classify tweets into different cyberbullying categories. It analyzes tweet text and predicts the category that best matches the input.

## 🎯 Objectives

- Process and analyze text data.
- Convert text into numerical features using TF-IDF.
- Train a machine learning classification model.
- Evaluate model performance using standard classification metrics.
- Predict cyberbullying categories for new text.

## 📂 Dataset

The dataset contains two columns:

- `tweet_text`: The text of the tweet.
- `cyberbullying_type`: The category assigned to the tweet.

The dataset contains six categories:

- `not_cyberbullying`
- `age`
- `ethnicity`
- `gender`
- `religion`
- `other_cyberbullying`

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Matplotlib
- Seaborn
- Jupyter Notebook

## ⚙️ Project Workflow

1. Load and explore the dataset.
2. Clean and prepare the text data.
3. Split the data into training and testing sets.
4. Convert text into numerical features using TF-IDF.
5. Train a Logistic Regression classifier.
6. Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.
7. Predict categories for new text.

## 📊 Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

Actual evaluation results should be added here after running the notebook. No performance score is claimed in this README.

## 🚀 How to Run

1. Open the notebook `cyberbullying.ipynb` in this repository.
2. Open it in Google Colab.
3. Upload the required dataset when prompted.
4. Run each code cell in order.
5. Review the model evaluation results and test predictions.

## ⚠️ Limitations

- Predictions may be incorrect, especially when text is sarcastic, ambiguous, or context-dependent.
- The model depends on the quality and coverage of its training dataset.
- A predicted category does not prove that a tweet is cyberbullying.
- The model should not be used as the sole basis for moderation or disciplinary decisions.

## 🔮 Future Improvements

- Test additional machine learning models.
- Explore transformer-based NLP models.
- Improve handling of sarcasm and context.
- Build an interactive web application.
- Evaluate performance on new, unseen datasets.

## 👩‍💻 Author

**Ritika Suryavanshi**

GitHub: [ritikasuryavanshi3105-rgb](https://github.com/ritikasuryavanshi3105-rgb)

---

*This project is for educational and research purposes.*
