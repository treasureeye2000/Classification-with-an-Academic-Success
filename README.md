Academic Risk Prediction

The objective of this project is to predict the academic risk of students in higher education. Participants will build machine learning models to classify the academic risk level of students based on provided features.

Evaluation
Submissions are evaluated using the accuracy score. The goal is to accurately predict the class value of the target variable, which represents a categorical academic risk assessment.

Submission File
For each ID row in the test set, you must predict the class value of the Target. The submission file should contain a header and be in the following format:

python

id,Target
76518,Graduate
76519,Graduate
76520,Graduate
...

Dataset Description

The dataset for this competition (both train and test) was generated from a deep learning model trained on the "Predict Students' Dropout and Academic Success" dataset. Feature distributions are similar, but not identical, to the original dataset. Participants are encouraged to use the original dataset to explore differences and see if incorporating the original data in training improves model performance.

Files
    train.csv: The training dataset; Target is the categorical target variable.
    test.csv: The test dataset; your objective is to predict the class of Target for each row.
    sample_submission.csv: A sample submission file in the correct format.

    Load the Data:
        Load train.csv and test.csv into your preferred data analysis tool (e.g., Python, R).

    Build Your Model:
        Use the training data to build and train your machine learning model.

    Make Predictions:
        Use your trained model to predict the target values for the test data.

    Create Submission File:
        Format your predictions as shown in the submission file example and save it as submission.csv.

Programming Language

This project primarily uses Python for data analysis, model building, and prediction. Key libraries used include:

    pandas
    numpy
    scikit-learn
    matplotlib
    seaborn

What I Learned

Through this project, I gained valuable experience in:

    Handling and preprocessing large datasets
    Exploratory data analysis (EDA) to uncover insights and patterns
    Feature engineering to improve model performance
    Building and tuning machine learning models
    Evaluating model accuracy and making predictions
    Creating submission files for Kaggle competitions


Contact
For any questions or feedback, feel free to reach out to me at eugenekobuobi@gmail.com
