# Email Spam Detection

## Overview

This project aims to improve the email filtering system for an Internet Service Provider (ISP) by developing supervised machine learning models to accurately detect spam emails. Two classification models were created and evaluated: a Logistic Regression model and a Random Forest model.

## Project Structure

- `spam_detector.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, evaluation, and comparison.
- `README.md`: Project overview and instructions.

## Dataset

The dataset used for this project contains information about emails with two possible classifications: spam and not spam. It is available at [this link](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv).

## Installation

To run this project, you need to have the following libraries installed:

- pandas
- scikit-learn
- Jupyter Notebook

You can install these dependencies using pip:

    ```sh
pip install pandas scikit-learn notebook
    ```

## Usage

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/classification-challenge.git
    ```

2. Navigate to the project directory:

    ```sh
    cd classification-challenge
    ```

3. Open the Jupyter notebook:

    ```sh
    jupyter notebook spam_detector.ipynb
    ```

4. Follow the steps in the notebook to load the data, preprocess it, train the models, and evaluate their performance.


## Results
After training and evaluating both the logistic regression and random forest models, the following accuracy scores were obtained:

Logistic Regression Accuracy: log_reg_accuracy
Random Forest Accuracy: rf_accuracy
The Random Forest model performed better with an accuracy score of rf_accuracy, compared to the Logistic Regression model's accuracy score of log_reg_accuracy.

## Conclusion
The results confirmed the initial prediction that the Random Forest model would perform better than the Logistic Regression model. This demonstrates the effectiveness of ensemble methods like Random Forests in improving classification accuracy, especially in tasks such as spam detection where the relationships between features can be intricate and non-linear.

## Credits
This project was developed with the assistance of ChatGPT by OpenAI.

Thank you for using this project. If you have any questions or suggestions, feel free to open an issue or submit a pull request.
