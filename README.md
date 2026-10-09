# AI-Based Language Detection System 🌍

## About the Project

The **AI-Based Language Detection System** is a machine learning project that identifies the language of a given text. It uses Natural Language Processing (NLP) techniques to convert text into numerical features and a Multinomial Naive Bayes classifier to predict the language.

The system also displays a confidence score and the Top-3 probable language predictions to provide more information about its results.

## Features

* **Language Detection:** Predicts the language of user-input text.
* **Confidence Score:** Displays the model's highest predicted probability.
* **Top-3 Predictions:** Shows the three most probable language predictions.
* **Low-Confidence Warning:** Suggests entering a longer sentence when the confidence score is below 60%.
* **Machine Learning-Based Classification:** Uses a trained Multinomial Naive Bayes model.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Natural Language Processing (NLP)
* CountVectorizer
* Multinomial Naive Bayes
* Jupyter Notebook

## How It Works

1. Load the language dataset from a CSV file.
2. Check the dataset and its language distribution.
3. Convert text into numerical features using CountVectorizer.
4. Split the data into training and testing sets.
5. Train a Multinomial Naive Bayes classifier.
6. Evaluate the model's accuracy.
7. Predict the language of new text.
8. Display the confidence score and Top-3 predictions.

## Project Structure

```text
language_detection/
├── Language_Detector.ipynb
├── language.csv
└── README.md
```

## How to Run

1. Download or clone this repository.

2. Make sure `Language_Detector.ipynb` and `language.csv` are in the same folder.

3. Install the required libraries:

   ```bash
   pip install pandas numpy scikit-learn jupyter
   ```

4. Open the notebook in Jupyter Notebook or VS Code.

5. Run the notebook cells in order.

6. Enter a text when prompted to see the predicted language, confidence score, and Top-3 predictions.

## Machine Learning Algorithm

**Multinomial Naive Bayes** is used for text classification. CountVectorizer transforms text into word-count features that the classifier can learn from.

## Future Improvements

* Add multilingual text translation.
* Develop an interactive web interface using Streamlit.
* Compare multiple machine learning algorithms.
* Improve performance on short or ambiguous text.

## Note

The confidence score represents the model's predicted probability, not a guarantee that the prediction is correct. Results depend on the dataset and the input text.



B.Tech Computer Science and Engineering
