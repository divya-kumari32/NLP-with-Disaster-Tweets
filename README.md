# NLP-with-Disaster-Tweets

## Disaster Tweet Classification

## Introduction
This project is based on the [Kaggle competition "Real or Not? NLP with Disaster Tweets"](https://www.kaggle.com/competitions/nlp-getting-started/overview). The goal is to build a machine-learning model that can predict whether a given tweet is about a real disaster or not.

## Project Structure
The project follows these main steps:
1. **Data Loading**: Importing the `train.csv` and `test.csv` datasets.
2. **Text Cleaning**: Preprocessing the tweet text data by:
    - Removing URLs
    - Removing special characters and numbers
    - Converting text to lowercase
3. Further steps will include exploratory data analysis, feature engineering, model selection, and model evaluation.

## Installation
To run this project, you need to have Python installed on your system, along with the following libraries:
- NumPy: `pip install numpy`
- Pandas: `pip install pandas`

## Usage
To execute the project:
1. Clone the repository to your local machine.
2. Ensure that the following data files are placed in the correct directory:
    - `train.csv`
    - `test.csv`
    - `sample_submission.csv`
3. Run the Jupyter notebook cell by cell to preprocess the data, train the model, and make predictions.

## Results
The notebook includes various machine learning models and their evaluation. The metrics used to evaluate the models have accuracy, precision, recall, and F1 score. Visualizations such as confusion matrices and ROC curves are also provided to analyze the model performance.

## Conclusion
The notebook concludes by discussing the results obtained from different models and suggestions for further improvements.

## Credits
This project is part of the Kaggle competition mentioned above and is intended for educational purposes.

## License
[MIT](https://choosealicense.com/licenses/mit/)

