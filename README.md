# Chance of Admission Prediction

This project aims to predict the **Chance of Admission** to a university based on various factors such as GRE score, TOEFL score, university rating, SOP (Statement of Purpose), LOR (Letter of Recommendation), CGPA, and research experience. The model is built using a linear regression approach.

## Dataset

The dataset used in this project contains the following columns:

- **Serial No**: Unique identifier for each entry
- **GRE Score**: GRE exam score of the applicant
- **TOEFL Score**: TOEFL exam score of the applicant
- **University Rating**: Rating of the university (1 to 5 scale)
- **SOP**: Statement of Purpose strength (1 to 5 scale)
- **LOR**: Letter of Recommendation strength (1 to 5 scale)
- **CGPA**: Cumulative Grade Point Average of the applicant
- **Research**: Research experience (0 = No, 1 = Yes)
- **Chance of Admit**: Probability of admission (target variable)

### Example of Data

| Serial No | GRE Score | TOEFL Score | University Rating | SOP | LOR | CGPA | Research | Chance of Admit |
|-----------|-----------|-------------|-------------------|-----|-----|------|----------|-----------------|
| 1         | 337       | 118         | 4                 | 4.5 | 4.5 | 9.65 | 1        | 0.92            |
| 2         | 324       | 107         | 4                 | 4.0 | 4.5 | 8.87 | 1        | 0.76            |
| 3         | 316       | 104         | 3                 | 3.0 | 3.5 | 8.00 | 1        | 0.72            |
| ...       | ...       | ...         | ...               | ... | ... | ...  | ...      | ...             |

## Project Workflow

1. **Data Loading**: The dataset is loaded from a CSV file hosted on GitHub.
2. **Data Preprocessing**: The target variable (`Chance of Admit`) is separated from the features. The data is then split into training and testing sets.
3. **Model Training**: A **Linear Regression** model is trained on the training data to predict the chance of admission.
4. **Prediction**: The trained model is used to predict the `Chance of Admit` for the test data.
5. **Model Evaluation**: The model is evaluated using the following metrics:
   - **Mean Absolute Error (MAE)**
   - **Mean Absolute Percentage Error (MAPE)**
   - **Mean Squared Error (MSE)**

## Installation

To run this project, you need to have Python installed on your machine along with the required libraries. You can install the necessary libraries using `pip`:

```bash
pip install pandas scikit-learn

![image](https://github.com/user-attachments/assets/f1b76490-aa84-44ab-8448-ca28504d7354)

![image](https://github.com/user-attachments/assets/e512d25d-200c-4eaf-a9ec-9cc860cf4afc)

![image](https://github.com/user-attachments/assets/d73091c7-0fb0-4f70-b291-4377e8a413c5)


