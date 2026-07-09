# Iris Classification using KNN

**Iris Classification using KNN** is a machine learning project that implements the K-Nearest Neighbors (KNN) algorithm to classify iris flowers into three species based on their physical measurements.

This is a weekly task project from **Decode Labs Internship**.

## 📊 Project Overview

This project demonstrates the complete machine learning workflow for binary/multi-class classification using the famous Iris dataset. It covers data loading, preprocessing, model training, and comprehensive model evaluation.

## 🎯 Objective

Classify iris flowers into one of three species:
- **Setosa**
- **Versicolor**
- **Virginica**

Based on four features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

## 📋 Dataset

The project uses the **Iris dataset** from scikit-learn, which contains:
- **150 samples** (50 per species)
- **4 features** (measurements in cm)
- **3 target classes** (iris species)

Dataset split:
- Training set: **70%** (105 samples)
- Testing set: **30%** (45 samples)

## 🛠️ Technologies Used

- **Python 3**
- **scikit-learn** - Machine learning library
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** & **seaborn** - Data visualization

## 📝 Project Structure

The notebook contains 4 main sections:

### 1. Load the Iris Dataset
- Imports the Iris dataset from scikit-learn
- Displays the first 5 rows of the dataset
- Shows target species names

### 2. Split the Dataset
- Divides data into training (70%) and testing (30%) sets
- Uses stratified sampling to maintain class distribution
- Sets random_state=42 for reproducibility

### 3. Train the KNN Model
- Initializes K-Nearest Neighbors classifier with **k=5**
- Trains the model on the training dataset
- The model learns patterns from 105 training samples

### 4. Evaluate the Model
- Makes predictions on the test set
- Generates classification report (precision, recall, F1-score)
- Displays confusion matrix
- Visualizes confusion matrix as a heatmap

## 🚀 How to Run

### Prerequisites
```bash
pip install pandas scikit-learn numpy matplotlib seaborn
```

### Usage
1. Open the Jupyter notebook: `Iris Classification using KNN.ipynb`
2. Run all cells sequentially (Cell 1 → Cell 10)
3. View the classification results and confusion matrix visualization

### In Google Colab
Click the "Open in Colab" button at the top of the notebook to run it directly in Google Colab without local setup.

## 📊 Expected Results

The KNN classifier with k=5 typically achieves:
- **High accuracy** on the Iris dataset (usually >95%)
- **Perfect or near-perfect classification** on test samples
- Clear confusion matrix showing minimal misclassifications

### Example Output
- Classification report with precision, recall, and F1-scores for each species
- Confusion matrix visualization highlighting model performance
- Heatmap showing prediction accuracy per class

## 🔍 Key Insights

- **KNN Algorithm**: A simple, non-parametric supervised learning algorithm
- **k=5**: Number of nearest neighbors to consider for classification
- **Stratified Split**: Ensures each train/test set has representative samples of all classes
- **Iris Dataset**: One of the most famous datasets in machine learning, perfect for beginners

## 📈 Model Performance Metrics

The evaluation includes:
- **Accuracy**: Overall correct predictions
- **Precision**: Correctness of positive predictions per class
- **Recall**: Ability to find all positive instances
- **F1-Score**: Harmonic mean of precision and recall
- **Confusion Matrix**: Shows where the model makes mistakes

## 📚 References

- [Scikit-learn KNN Documentation](https://scikit-learn.org/stable/modules/neighbors.html)
- [Iris Dataset Documentation](https://scikit-learn.org/stable/datasets/toy_dataset.html#iris-dataset)
- [KNN Algorithm Explained](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)

## 👨‍💻 Author

**Taskeen Mustafa**

---

*Last Updated: 2026*
