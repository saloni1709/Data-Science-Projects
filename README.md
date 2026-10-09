# 📊 Data Science Projects

This repository contains data science and machine learning projects focused on data analysis, text classification, and extracting meaningful insights using Python and related technologies.

---

# 1. 🌍 AI-Based Language Detection System

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

6. Enter text when prompted to see the predicted language, confidence score, and Top-3 predictions.

## Machine Learning Algorithm

**Multinomial Naive Bayes** is used for text classification. CountVectorizer transforms text into word-count features that the classifier can learn from.

## Future Improvements

* Add multilingual text translation.
* Develop an interactive web interface using Streamlit.
* Compare multiple machine learning algorithms.
* Improve performance on short or ambiguous text.

## Note

The confidence score represents the model's predicted probability, not a guarantee that the prediction is correct. Results depend on the dataset and the input text.

---

# 2. 🛒 E-commerce Data Analysis

## About the Project

The **E-commerce Data Analysis** project focuses on analyzing e-commerce sales data to understand sales performance, customer purchasing behavior, and business trends. It involves data cleaning, exploratory data analysis, and data visualization to extract meaningful insights from the dataset.

The project also includes a sales dashboard in PDF format to present business information in a clear and understandable way.

## Features

* **Data Cleaning:** Cleans and prepares raw e-commerce data for analysis.
* **Exploratory Data Analysis:** Explores the dataset to identify patterns and trends.
* **Sales Analysis:** Analyzes sales data to understand business performance.
* **Data Visualization:** Presents information through visualizations and a sales dashboard.
* **Business Insights:** Helps understand sales trends and customer purchasing behavior.

## Technologies Used

* Python
* Pandas
* Jupyter Notebook
* Microsoft Excel
* Data Visualization
* Power BI *(include only if used to create the dashboard)*

## How It Works

1. Load the raw e-commerce dataset from an Excel file.
2. Inspect the dataset and identify data quality issues.
3. Clean and preprocess the data.
4. Save the cleaned data as a CSV file.
5. Perform exploratory data analysis using Python and Pandas.
6. Analyze sales data and identify patterns.
7. Present the results through a sales dashboard.
8. Export the dashboard as a PDF file for easy viewing.

## Project Structure

```text
Ecommerce_Data_Analysis/
├── Clean_Ecommerce.csv
├── Ecommerce.ipynb
├── Ecommerce_Sales_Dashboard.pdf
├── Ecommerce_Unclean_Project.xlsx
└── README.md
```

## How to Run

1. Download or clone this repository.

2. Make sure the project files are available in the same folder.

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Open `Ecommerce.ipynb` in Jupyter Notebook, Google Colab, or VS Code.

5. Ensure the dataset paths used in the notebook are correct.

6. Run the notebook cells in order to explore the data analysis.

7. Open `Ecommerce_Sales_Dashboard.pdf` to view the sales dashboard.


## Data Analysis

The project focuses on exploring e-commerce data, cleaning the dataset, analyzing sales-related information, and presenting findings through visualizations.

The specific insights depend on the columns available in the dataset and the analysis performed in the notebook.

## Future Improvements

* Add more detailed customer segmentation.
* Include sales forecasting.
* Explore additional business performance metrics.
* Develop an interactive dashboard.
* Improve visualizations to communicate insights more effectively.

## Note

The quality of the analysis depends on the available dataset, data-cleaning process, and selected analytical methods. The dashboard presents the results of the analysis in a visual format.


⭐ If you find these projects useful, feel free to explore the repository!
