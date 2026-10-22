# BeanSense AI — Dry Bean Classification

A Machine Learning project that predicts dry bean varieties using 16 numerical features and an interactive Gradio web application.

##  About the Project

BeanSense AI is a machine learning classification project developed to identify dry bean varieties based on their physical measurements.

The project uses the Dry Bean Dataset and compares 10 classification algorithms to select the best-performing model.

After comparing the algorithms, Logistic Regression achieved the best result in the model evaluation and was selected as the final model for prediction.

The trained model is integrated with a Gradio web interface where users can enter 16 feature values in a single input box and receive a predicted bean class.

##  Project Objectives

- Classify dry beans into their respective varieties.
- Compare 10 different classification algorithms.
- Evaluate model performance using classification metrics.
- Select the best-performing algorithm based on evaluation results.
- Build an interactive web application using Gradio.

##  Dataset Information

- **Dataset:** Dry Bean Dataset
- **Total Samples:** 13,543
- **Input Features:** 16 numerical features
- **Target Variable:** `Class`
- **Number of Classes:** 7

### Bean Classes

- DERMASON
- SIRA
- SEKER
- HOROZ
- CALI
- BARBUNYA
- BOMBAY

### Input Features

`Area`, `Perimeter`, `MajorAxisLength`, `MinorAxisLength`, `AspectRation`, `Eccentricity`, `ConvexArea`, `EquivDiameter`, `Extent`, `Solidity`, `roundness`, `Compactness`, `ShapeFactor1`, `ShapeFactor2`, `ShapeFactor3`, `ShapeFactor4`

##  Machine Learning Workflow

1. Data Collection
2. Data Understanding
3. Data Preprocessing
4. Feature and Target Separation
5. Train-Test Split
6. Training 10 Classification Algorithms
7. Model Evaluation and Comparison
8. Selection of the Best-Performing Model
9. Saving the Trained Model
10. Building the Gradio Web Application

## 🤖 Algorithms Compared

The following 10 classification algorithms were evaluated:

1. Logistic Regression
2. Perceptron
3. Passive-Aggressive Classifier
4. Linear Discriminant Analysis (LDA)
5. Quadratic Discriminant Analysis (QDA)
6. Bernoulli Naive Bayes
7. Complement Naive Bayes
8. Multinomial Naive Bayes
9. Ridge Classifier
10. Gaussian Naive Bayes

###  Final Model: Logistic Regression

After evaluating all 10 algorithms, Logistic Regression achieved the best result in this project's model comparison and was selected as the final model.

The selected model is used in the Gradio application to predict dry bean varieties from the 16 input features.

**Note:** The best-performing model is determined by the evaluation results obtained in this project. Actual performance can vary depending on the train-test split, preprocessing, and evaluation metrics.

##  Model Evaluation

The models were evaluated using classification performance metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Logistic Regression achieved approximately **89.7% accuracy** on the test set in the recorded evaluation.

##Web Application Features

- Simple and user-friendly interface.
- Green-themed navigation and design.
- Single input box for all 16 feature values.
- Input validation for the required number of values.
- One-click bean class prediction.
- Clear button to reset the input.
- About Project and Contact sections.

##  Technologies Used

- Python
- Pandas
- Scikit-learn
- Joblib
- Gradio

##  Project Structure

```text
BeanSense-AI/
│
├── app.py
├── dry_bean_model.pkl
├── requirements.txt
└── README.md
```

##  Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project Folder

```bash
cd YOUR_PROJECT_FOLDER
```

### 3. Install Dependencies

```bash
pip install gradio pandas scikit-learn joblib
```

You can also install the packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

Open the local URL displayed in the terminal to use the application.

##  How to Use

1. Open the BeanSense AI web application.
2. Enter the 16 numerical feature values in the input box.
3. Separate each value with a comma.
4. Click **Predict Bean Class**.
5. View the predicted dry bean variety.

Make sure the input values follow the exact feature order used during model training.

##  Contact

**Developer:** Piyal Baray

**Email:** piyalbaray314@gmail.com

##  Future Improvements

- Deploy the application online.
- Add model performance visualizations.
- Improve input validation and user guidance.
- Add a model comparison chart.
- Explore hyperparameter tuning for further performance improvements.

##  License

This project is intended for educational and portfolio purposes. Add a suitable open-source license if you want others to reuse or distribute the code.

---

**Developed by Piyal Baray | BeanSense AI — Machine Learning Classification Project**
