# Diabetes Prediction Using Machine Learning

This repository contains a project aimed at predicting the likelihood of diabetes using machine learning techniques. It is designed for educational purposes, making it ideal for beginners looking to learn and apply data science and machine learning concepts in a healthcare context.

## Features
- **Data Preprocessing**: Includes handling missing values, feature scaling, and data transformation.
- **Exploratory Data Analysis (EDA)**: Provides visualizations and statistical summaries to understand the dataset.
- **Machine Learning Model**: Implements supervised learning algorithms for diabetes prediction.
- **Prediction Workflow**: Step-by-step process to build and evaluate the predictive model.

## Dataset
The project uses the `diabetes.csv` dataset, which contains features related to diabetes diagnostics, such as:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

## Requirements
To run this project, ensure you have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

You can install these dependencies using the following command:
```bash
pip install -r requirements.txt
```

## Algorithms Used
This project uses the following algorithm for diabetes prediction:
- **Logistic Regression**: A statistical method for binary classification, used to predict whether a person is diabetic or not.

## Prediction Workflow
1. **Data Loading**: Load the dataset from the CSV file.
2. **Data Preprocessing**: Handle missing values, normalize features, and split the data into training and testing sets.
3. **Exploratory Data Analysis**: Visualize data distributions and correlations using Matplotlib and Seaborn.
4. **Model Training**: Train a Logistic Regression model using the scikit-learn library.
5. **Evaluation**: Evaluate the model's accuracy, precision, recall, and F1-score using the test dataset.
6. **Prediction**: Use the trained model to predict diabetes based on new input data.

## Getting Started
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/smit-faldu/diabetes-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd diabetes-prediction
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter notebook:
   ```bash
   jupyter notebook index.ipynb
   ```

5. Follow the steps in the notebook to explore the dataset, preprocess data, and train the model.

## Project Structure
```
.
├── diabetes.csv         # Dataset file
├── index.ipynb          # Jupyter notebook with analysis and model implementation
├── requirements.txt     # List of dependencies
├── README.md            # Project documentation
```

## Contributing
Contributions are welcome! If you find any issues or want to improve the project, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The dataset used in this project is publicly available and intended for educational purposes.
- Special thanks to the open-source community for providing the tools and libraries used in this project.
