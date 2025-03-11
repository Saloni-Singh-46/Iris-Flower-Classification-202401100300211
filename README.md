# Iris-Flower-Classification-202401100300211
# Iris Flower Classification

## Overview
This project is a **Machine Learning** classification task to predict the species of an **Iris flower** based on its physical attributes (**sepal length, sepal width, petal length, petal width**). It uses a **Random Forest Classifier** for prediction and provides data visualization and model evaluation.

## Dataset
The dataset used is the **Iris Dataset**, which contains:
- 150 samples
- 4 features: **sepal length, sepal width, petal length, petal width**
- 3 classes (species): **Setosa, Versicolor, Virginica**

## Project Structure
```
├── SALONI_SINGH_2428CSEAI2455_  # Main Python script for training and evaluation
├── iris_data.csv         # Dataset file
├── README.md               # Project documentation
```

## Report
This file contains a report pdf which provide brief description about this project and contains the code, screenshot of output.

### Prerequisites
Ensure you have Python installed along with the required libraries. You can install them using:
```sh
pip install pandas numpy seaborn matplotlib scikit-learn
```

### Running the Program
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/iris-flower-classification.git
   ```
2. Navigate to the project directory:
   ```sh
   cd iris-flower-classification
   ```
3. Run the script:
   ```sh
   python iris_classification.py
   ```

## Methodology
1. **Data Preprocessing**
   - Load the dataset and check for missing values.
   - Encode categorical target labels.
   - Ensure data is balanced for model training.
2. **Exploratory Data Analysis (EDA)**
   - Generate plots using Seaborn to visualize feature relationships.
3. **Model Training & Evaluation**
   - Split the dataset into training (80%) and testing (20%).
   - Train a **Random Forest Classifier** with optimized hyperparameters.
   - Evaluate the model using accuracy, classification report, and confusion matrix.
4. **Feature Importance Analysis**
   - Display feature importance using bar charts.

## Results
- Model accuracy is displayed in the output.
- A confusion matrix visualizes the classification performance.
- Feature importance analysis shows which features contribute most to predictions.

## Future Improvements
- Experiment with different classifiers (SVM, KNN, Logistic Regression).
- Tune hyperparameters for better accuracy.
- Deploy as a web app using Flask or Streamlit.

## Contributing
Feel free to fork this repository and submit a pull request with improvements!

## License
This project is open-source.

