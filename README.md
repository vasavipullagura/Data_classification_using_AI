# Data_classification_using_AI
# 🌿 FloraClass AI — Intelligent Flower Classification

### An AI-Powered Machine Learning Project Using the Iris Dataset

## 📌 Project Overview

**FloraClass AI** is a machine learning project that uses Artificial Intelligence (AI) to classify flower species based on their physical measurements.

The project uses the Iris dataset and a **Decision Tree Classification algorithm** to predict the species of a flower based on four input features:

- Sepal length
- Sepal width
- Petal length
- Petal width

By learning patterns from existing flower measurements, the model can predict the species of a new flower automatically.

This project demonstrates how machine learning can transform numerical data into meaningful classifications without manually defining every classification rule.

## 🎯 Objectives

- Implement AI-based data classification using Python.
- Understand the fundamentals of supervised machine learning.
- Train a Decision Tree Classifier using the Iris dataset.
- Evaluate model performance using classification accuracy.
- Predict the species of a flower from its measurements.
- Explore how machine learning identifies patterns in data.

## ✨ Key Features

- **Automated Classification:** Predicts flower species using a trained machine learning model.
- **Built-in Dataset:** Uses the Iris dataset provided by Scikit-learn.
- **Data Exploration:** Displays dataset dimensions, feature names, target classes, and sample records.
- **Model Training:** Learns classification rules from labeled training data.
- **Accuracy Evaluation:** Compares predicted labels with actual labels.
- **Real-Time Prediction Example:** Demonstrates how to classify a new flower using its measurements.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Organizing and displaying dataset information |
| Scikit-learn | Dataset loading, model training, and evaluation |
| Decision Tree Classifier | Predicting flower species |
| Iris Dataset | Training and testing data |

## 🌸 Dataset Description

The project uses the Iris dataset available through `sklearn.datasets`.

The dataset contains **150 flower samples**, with four numerical features per sample and three species classes.

### Input Features

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal in centimeters |
| Sepal Width | Width of the sepal in centimeters |
| Petal Length | Length of the petal in centimeters |
| Petal Width | Width of the petal in centimeters |

### Target Classes

The model classifies flowers into three species:

- Setosa
- Versicolor
- Virginica

## ⚙️ Project Workflow

The project follows these steps:

1. **Import Libraries:** Load Pandas and the required Scikit-learn modules.
2. **Load Dataset:** Retrieve the Iris dataset.
3. **Explore Data:** Display sample records, feature names, and target classes.
4. **Split Dataset:** Allocate 80% of the data for training and 20% for testing.
5. **Create Model:** Initialize a Decision Tree Classifier.
6. **Train Model:** Fit the classifier using the training data.
7. **Make Predictions:** Predict species for the test dataset.
8. **Evaluate Accuracy:** Compare predicted labels with actual labels.
9. **Classify a New Flower:** Predict the species from a new set of measurements.

## 🧠 Machine Learning Algorithm

### Decision Tree Classifier

A Decision Tree is a supervised machine learning algorithm that learns decision rules from labeled examples.

It separates data into branches based on feature values until it reaches a predicted class.

In this project, the model learns relationships between flower measurements and their corresponding species.

**Why use a Decision Tree?**

- Easy to understand and interpret.
- Suitable for classification problems.
- Works with numerical features.
- Requires minimal data preprocessing for this dataset.
- Can learn nonlinear decision boundaries.

## 📂 Project Structure

```text
FloraClass-AI/
│
├── project2.py
├── requirements.txt
├── README.md
└── .gitignore
```

## 🚀 Installation and Execution

### Prerequisites

Install Python 3.9 or a compatible newer version.

### Step 1: Clone the Repository

```bash
git clone <your-repository-url>
```

### Step 2: Navigate to the Project Folder

```bash
cd FloraClass-AI
```

### Step 3: Install Dependencies

Create a `requirements.txt` file containing:

```text
pandas
scikit-learn
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

### Step 4: Run the Project

```bash
python project2.py
```

The program will display dataset information, training and testing sample counts, actual labels, predicted labels, model accuracy, and the predicted species of a new flower.

## 🔬 Example Prediction

The project predicts a flower species using these measurements:

```python
new_flower = [[5.1, 3.5, 1.4, 0.2]]
```

The input represents:

| Feature | Measurement |
|---|---:|
| Sepal Length | 5.1 cm |
| Sepal Width | 3.5 cm |
| Petal Length | 1.4 cm |
| Petal Width | 0.2 cm |

The trained model predicts the species from these measurements.

For this example, the expected prediction from the Iris dataset is **Setosa**.

## 📊 Model Evaluation

The model uses the `accuracy_score` function to evaluate predictions on the test dataset.

Accuracy is calculated as:

**Accuracy = (Correct Predictions / Total Predictions) × 100**

The program displays the calculated accuracy as a percentage.

The actual accuracy depends on the training data, test split, and model configuration.

## 🌍 Applications

This project demonstrates fundamental concepts that can be extended to:

- Plant species identification.
- Agricultural data classification.
- Environmental data analysis.
- Automated quality classification.
- Educational machine learning applications.
- Classification of other structured datasets.

These are potential extensions rather than features implemented in the current code.

## 🔮 Future Enhancements

- [ ] Add a graphical user interface for entering flower measurements.
- [ ] Visualize the decision tree.
- [ ] Generate a confusion matrix.
- [ ] Display precision, recall, and F1-score.
- [ ] Compare Decision Tree, Random Forest, and Logistic Regression models.
- [ ] Allow users to classify multiple flowers from a CSV file.
- [ ] Build a web application for interactive predictions.

## 🔐 Responsible AI

The model learns from the dataset used during training. Its predictions should therefore be understood in the context of that dataset.

Testing the model on unseen data and reviewing its performance helps identify classification errors and understand its limitations.

## 👨‍💻 Author

**Your Name**

GitHub: [Your GitHub Profile](https://github.com/your-username)

## 📜 License

This project can be distributed under the MIT License. Add a `LICENSE` file if you choose to use that license.

---

### 🌱 Project Vision

**"Turning flower measurements into intelligent predictions through the power of AI."**

⭐ If you find this project useful, consider starring the repository.
