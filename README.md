
# Diabetes Prediction SVM System by Liz

## Overview

This project is a Diabetes Prediction System that employs Support Vector Machines (SVM) for classification. It's designed to predict the likelihood of a person having diabetes based on various features, including Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age.

The goal of this project is to create a simple yet effective tool for predicting diabetes, which can be helpful in early diagnosis and preventive healthcare.

## Table of Contents

- Features
- Installation
- Usage
- Data
- Sample Test Data
-Contributing
-Licence

## Features

- Train and test a Support Vector Machine model for diabetes prediction.
- Evaluate the model's performance with accuracy, precision, recall, and F1-score.
- User-friendly command-line interface.

## Installation

1. Clone the repository to your local machine using the following command:

git clone https://github.com/Elizabeth346/Diabetes-Prediction-SVM.git

css
Copy code

2. Change to the project directory:

cd Diabetes-Prediction-SVM

arduino
Copy code

3. Install the required Python libraries using pip:

pip install -r requirements.txt

css
Copy code

## Usage

1. Open a terminal and navigate to the project directory.

2. Run the main script to train and test the SVM model:

python predict_diabetes.py

vbnet
Copy code

3. Follow the on-screen instructions to input patient data for prediction.

4. The program will display the prediction results and evaluation metrics.

## Data

The dataset used for training and testing the SVM model can be found in the `data` directory. You can use your own dataset by replacing the provided data files. Make sure the dataset format matches the one used in the project.

### Sample Test Data

Here is a sample test data set that you can use to test the system:

| Pregnancies | Glucose | BloodPressure | SkinThickness | Insulin | BMI | DiabetesPedigreeFunction | Age | Outcome |
|-------------|---------|---------------|--------------|---------|-----|--------------------------|-----|---------|
| 5           | 116     | 74            | 0            | 0       | 25.6| 0.201                  | 30  | 0       |
| 3           | 78      | 50            | 32           | 88      | 31  | 0.248                  | 26  | 1       |
| 10          | 115     | 0             | 0            | 0       | 35.3| 0.134                  | 29  | 0       |
| 2           | 197     | 70            | 45           | 543     | 30.5| 0.158                  | 53  | 1       |
| 8           | 125     | 96            | 0            | 0       | 0   | 0.232                  | 54  | 1       |
| 4           | 110     | 92            | 0            | 0       | 37.6| 0.191                  | 30  | 0       |
| 10          | 168     | 74            | 0            | 0       | 38  | 0.537                  | 34  | 1       |
| 10          | 139     | 80            | 0            | 0       | 27.1| 1.441                  | 57  | 0       |
| 1           | 189     | 60            | 23           | 846     | 30.1| 0.398                  | 59  | 1       |

## Contributing

Contributions are welcome! If you would like to improve this project or add new features, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-name`
5. Create a pull request, and we'll review your changes.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.

---

