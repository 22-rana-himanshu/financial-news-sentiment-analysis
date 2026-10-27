# 📈 Financial News Sentiment Analysis Using Machine Learning

A Natural Language Processing (NLP) project that classifies financial text sentiment using TF-IDF feature extraction and Logistic Regression.

## 📌 About the Project

Financial news headlines can influence how investors perceive markets, companies, and economic events. This project uses machine learning to classify financial text into sentiment categories based on a labeled dataset.

The model learns patterns from previously labeled financial sentences and predicts the sentiment of new headlines.

## 🎯 Project Objectives

- Clean and preprocess financial text.
- Remove stop words and unnecessary characters.
- Convert text into numerical features using TF-IDF.
- Train a Logistic Regression classification model.
- Evaluate the model using accuracy, precision, recall, and F1-score.
- Predict sentiment for new financial headlines.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Google Colab

## 📂 Project Workflow

1. **Data Loading:** Load financial text and sentiment labels from a CSV file.
2. **Text Preprocessing:** Convert text to lowercase, remove special characters and numbers, and filter English stop words.
3. **Feature Extraction:** Use TF-IDF with unigrams and bigrams, with up to 5,000 features.
4. **Model Training:** Train Logistic Regression using an 80/20 train-test split.
5. **Model Evaluation:** Generate accuracy, a classification report, and predictions on test data.
6. **Sentiment Prediction:** Predict the sentiment and model probability for a new financial headline.

## 📊 Model Evaluation

The model evaluates its predictions using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix (imported in the notebook)

**Actual results:** Add the accuracy and classification metrics produced when you run the notebook. Results depend on the dataset and train-test split.

## 💻 Example Prediction

Example headline:

> Tech giant reports record revenue, beating market estimates.

The notebook passes this headline to the trained model and returns:
- Predicted sentiment
- Maximum predicted class probability

The exact prediction and probability should be taken from the notebook output.

**Note:** Model probability is not necessarily a calibrated measure of real-world confidence.

## 📁 Project Files

- `financial_news_sentiment_analysis.ipynb` — Main notebook containing preprocessing, model training, evaluation, and inference.
- `data.csv` — Dataset file, if permitted to redistribute.
- `requirements.txt` — Python dependencies.

## 🚀 How to Run

1. Clone or download this repository.
2. Install the dependencies:

   ```bash
   pip install pandas numpy nltk scikit-learn
   ```

3. Ensure `data.csv` is available in the notebook's working directory.
4. Update the dataset path if necessary.
5. Run the notebook cells in order.

The notebook downloads the NLTK English stopwords resource when executed.

## 📂 Dataset Requirements

The CSV file must contain these columns:

- `Sentence` — Financial text or headline.
- `Sentiment` — The corresponding sentiment label.

The code reads the CSV using `latin-1` encoding. Update the column names or encoding if your dataset uses a different format.

## 👨‍💻 Author

**Himanshu Rana**  
M.Sc. Data Science Student

- GitHub: https://github.com/22-rana-himanshu
- Google Colab: https://colab.research.google.com/drive/1a3iL93j_cxhvM54jxF46yND4RpYepkW2

---

⭐ This project demonstrates practical applications of NLP, text preprocessing, feature extraction, and supervised machine learning.
