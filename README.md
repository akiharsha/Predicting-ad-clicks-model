# Logistic Regression: Ad Click Prediction

This project demonstrates how to use **logistic regression** to predict whether a user will click on an online advertisement. The model is built and evaluated using Python and popular data science libraries.

## 📄 Project Overview

Given a user's demographic and behavioral features, the model predicts the likelihood of an ad click (`Clicked on Ad`: 1 = Clicked, 0 = Not Clicked).

### **Dataset Features**
- `Daily Time Spent on Site`: Minutes user spends daily on the website
- `Age`: Age of the user
- `Area Income`: Average income of the user's geographic area
- `Daily Internet Usage`: Average minutes per day user spends on the internet
- `Ad Topic Line`: Headline of the advertisement
- `City`: User's city
- `Male`: 1 if user is male, 0 otherwise
- `Country`: User's country
- `Timestamp`: Time when user clicked or closed the ad
- `Clicked on Ad`: Target variable (1 if clicked, 0 if not)

## 🚀 Steps in the Notebook

1. **Data Loading & Exploration**
    - Import required libraries
    - Load the dataset (`advertising.csv`)
    - Explore data types and summary statistics
    - Visualize distributions and feature relationships

2. **Data Preparation**
    - Select relevant features
    - Split data into training and test sets

3. **Model Building**
    - Train a logistic regression model using scikit-learn

4. **Evaluation**
    - Predict on the test set
    - Evaluate using classification metrics (precision, recall, f1-score, accuracy)

### **Sample Evaluation Output**

```
             precision    recall  f1-score   support

          0       0.87      0.96      0.91       162
          1       0.96      0.86      0.91       168

avg / total       0.91      0.91      0.91       330
```

## 📊 Example Visualizations

- Distribution of user ages
- Joint plots of features (e.g., Area Income vs Age, Daily Time Spent on Site vs Age)
- Pair plots colored by ad click outcome

## 🛠️ How to Run

You can run this project locally or on [Google Colab](https://colab.research.google.com/):

1. **Clone the repository or upload the notebook to Colab**

2. **Upload the `advertising.csv` dataset**
    - To Colab: Use the file upload feature or `from google.colab import files; files.upload()`

3. **Install dependencies (if needed)**
    ```python
    !pip install pandas numpy matplotlib seaborn scikit-learn
    ```

4. **Run all cells in the notebook**

## 📂 Files

- `Logistic Regression Project.ipynb` — Main notebook
- `advertising.csv` — Dataset (make sure it is in the same directory or uploaded in Colab)

## ✨ Credits

- Dataset and project structure inspired by typical machine learning course exercises.

---

**For questions or improvements, feel free to open an issue or pull request!**
