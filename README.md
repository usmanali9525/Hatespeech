# Hate Speech Detection
This repository contains code for a Hate Speech Detection project using the Natural Language Toolkit (NLTK) and scikit-learn libraries. The project aims to classify text data into different categories such as "Hate Speech," "Offensive Language," and "No Hate and Offensive."

## Prerequisites
Make sure you have the following libraries installed:

1. nltk
2. pandas
3. numpy
4. sklearn
You can install these libraries using pip:
```
pip install nltk pandas numpy scikit-learn
```
## Getting Started
Clone the repository:
```
git clone https://github.com/your-username/hate-speech-detection.git
```
Change into the project directory:
```
cd hate-speech-detection
```
Download the dataset "labeled_data.csv" and place it in the project directory.

Run the code:
```
python main.py
```
## Code Explanation
1. The code starts by importing the required libraries.
2. The dataset is loaded using pandas from the "labeled_data.csv" file.
3. The text data is preprocessed.
4. The dataset is split into training and testing sets using the train_test_split function.
5. A decision tree classifier is trained on the training data using the DecisionTreeClassifier class.
6. The accuracy of the classifier is calculated using the score method on the testing data.
7. The hate_speech_detection() function is defined to provide a simple interface for detecting hate speech using a Streamlit application.

The Streamlit application allows the user to enter a tweet, and the trained classifier predicts the corresponding label.
