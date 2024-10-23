## End to End Machine Learning Project
# Student Performance Prediction

This project aims to predict students' performance based on various input features like gender, race/ethnicity, parental education level, lunch type, test preparation, reading score, and writing score. The prediction model uses machine learning techniques to provide insights into students' future performance in exams.

## Dataset

The dataset used in this project (`stud.csv`) contains the following features:
- **Gender**: The gender of the student.
- **Race/Ethnicity**: The group/category the student belongs to.
- **Parental Level of Education**: The education level of the student's parents.
- **Lunch**: Whether the student receives free/reduced lunch or standard lunch.
- **Test Preparation Course**: Whether the student completed a test preparation course.
- **Reading Score**: The student's reading test score.
- **Writing Score**: The student's writing test score.

## Project Structure

- `src/`: Contains the source code for data ingestion, transformation, and prediction.
- `notebooks/`: Jupyter notebooks for data analysis and exploration.
- `artifacts/`: Directory for model artifacts such as trained models and preprocessor.
- `stud.csv`: The dataset used for model training and evaluation.

## How to Use

1. Clone the repository.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the prediction pipeline by following the instructions in the `src/` directory.

## Model

The model used in this project is a supervised machine learning model trained using the `stud.csv` dataset. The preprocessing steps include scaling, encoding categorical variables, and splitting the dataset into training and testing sets. The final model is saved in the `artifacts/` folder for future use.

## Output of the Project

![Screenshot of the application]([images/output of project.png](https://github.com/minalmmm/End-to-End-Machine-Learning-Project-1/blob/main/output%20of%20project.png))

