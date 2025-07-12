# Spam SMS Detection

This project focuses on detecting spam SMS messages using machine learning techniques. The objective is to build a model that can accurately classify SMS messages as either spam or ham (not spam) based on their content.

## Use Case

Spam detection is an important problem in communication systems, as spam messages can be both annoying and potentially harmful. This project aims to automatically identify spam messages using data-driven approaches, helping improve message filtering and security.

## What Has Been Done

- **Exploratory Data Analysis (EDA):**
  - Investigated the structure and key characteristics of the UCL SMS spam dataset.
  - Visualized and summarized the distribution of spam vs. ham messages.

- **Feature Engineering:**
  - Processed and transformed raw text data into numerical features using techniques like TF-IDF and Count Vectorization.
  - Encoded labels for model training.

- **Model Building:**
  - Implemented a Naive Bayes (NB) classifier to distinguish between spam and ham messages.
  - Split the dataset into training and testing sets to evaluate model performance.
  - Assessed the model using metrics such as accuracy and confusion matrix.

## Getting Started

1. Clone this repository.
2. Install necessary Python packages (see the notebook for requirements).
3. Run the Jupyter notebook `sms-spam-detection.ipynb` to explore the analysis and model.

## Data Source

- The project uses the publicly available SMS Spam Collection Dataset from UCL.

## Files

- `sms-spam-detection.ipynb`: Main notebook containing code for EDA, feature engineering, and model training.
- `README.md`: Explanation and overview of the project.

## Results

- The Naive Bayes model provides a straightforward and effective approach for SMS spam detection, achieving solid accuracy on the test set.

---

Feel free to explore the notebook for detailed code and visualizations!
