# Algorithm Chains and Pipelines with Scikit-Learn 🔗🤖

This project demonstrates the use of **algorithm chains** and **pipelines** in **Scikit-Learn** for building and evaluating machine learning models. The goal is to streamline the process of data preprocessing, model training, and evaluation using pipelines. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **Scikit-Learn** to build and evaluate machine learning models using pipelines. 🤖🔗
- Leverages the **Breast Cancer** and **California Housing** datasets for training and validation. 🧠🔍
- Implements data preprocessing, model training, and evaluation using pipelines. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install scikit-learn mglearn
```

---

## Usage 🖥️

1. **Load Dataset**: The script loads the Breast Cancer and California Housing datasets.
2. **Preprocess Data**: Applies data preprocessing using pipelines.
3. **Build Models**: Defines and trains models using pipelines.
4. **Evaluate Models**: Evaluates the models' performance using cross-validation and grid search.
5. **Visualize Results**: Visualizes the results using heatmaps.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Loads and preprocesses the datasets.
  - Splits the data into training and test sets.

- **Model Definition**:
  - Defines pipelines for data preprocessing and model training.
  - Uses cross-validation and grid search for hyperparameter tuning.

- **Training**:
  - Trains the models using the training set.
  - Tracks cross-validation accuracy.

- **Evaluation**:
  - Evaluates the models' performance on the test set.
  - Prints the test accuracy.

- **Visualization**:
  - Visualizes the results using heatmaps.

---

## Results 📊

- **Cross-Validation Accuracy**: The models achieve high cross-validation accuracy.
- **Test Accuracy**: Evaluates the models' performance on the test set.
- **Heatmaps**: Visualizes the results of grid search.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Best cross-validation score: 0.98
Test set score: 0.97
Best parameters: {'svm__C': 1, 'svm__gamma': 1}
```

---

## Dependencies 📦

- `scikit-learn`
- `mglearn`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
