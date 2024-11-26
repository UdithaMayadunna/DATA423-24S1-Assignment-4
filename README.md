# DATA423-24S1-Assignment-4
This repository contains the solutions for DATA423-24S1 Assignment 4, a comprehensive data science assignment focusing on classification and quality control techniques using R and Python. The assignment is divided into three questions, each showcasing different tools and frameworks for data analysis and machine learning.

Assignment Overview
Question 1: Classification Using MLR3 (R)
This question involves translating a classification task originally implemented in the caret package to the MLR3 framework in R. The task includes:

Preprocessing a Kaggle dataset.

Splitting the data into training and testing sets (70/30 stratified split).
Handling imbalanced data using Borderline SMOTE.
Normalizing predictors and performing dimensionality reduction.
Building and tuning a Support Vector Machine (SVM) with a radial basis function kernel.
Constructing an MLR3 pipeline for automation.
Evaluating model performance using 10-fold cross-validation and a confusion matrix.

Deliverables:
R Notebook showcasing the implementation and results.
PDF or HTML file of the executed notebook.
Question 2: Classification Using Scikit-Learn (Python)
This question adapts the classification task to Python using the scikit-learn framework. The task includes:

Reading and preprocessing the dataset.
Stratified 70/30 train-test split.
Upsampling the minority class to handle data imbalance.
Normalizing features and performing dimensionality reduction.
Training and tuning an SVM with a radial basis function kernel.
Creating a pipeline to streamline preprocessing and model building.
Evaluating performance with 10-fold cross-validation and generating a confusion matrix.
Deliverables:
Jupyter Notebook (or Python code in an R Notebook) demonstrating the process.
PDF or HTML file of the executed notebook.
Question 3: Quality Control Analysis (R)
In this question, control charts are used to analyze server performance and model predictions. The provided monitor.csv dataset is used for the analysis. The task includes:

Adding a "day-of-the-year" column for grouping data.
Creating x-bar and s control charts for:
Memory usage of the server.
Prediction time of the model.
Stream of predictions.
Establishing control limits using the first 40 days of data.
Determining if the system is in control based on the charts.
Deliverables:
R Notebook with visualizations and interpretations.
PDF or HTML file of the executed notebook.
Technologies and Tools
R: MLR3 framework, qicharts2, and associated libraries for machine learning and quality control.
Python: Scikit-learn library for machine learning pipelines and classification.
Visualization Tools: Confusion matrix, control charts, and various summary statistics.
Submission Details
The repository contains:

Solution notebooks for each question.
PDF/HTML files with successfully executed results.
A single compressed zip file as required for submission.
How to Use

Clone the repository:
bash
Copy code
git clone https://github.com/<UdithaMayadunna>/DATA423-Assignment4.git
Navigate to the respective folder for each question to explore the solutions.
Run the R or Python notebooks in the respective environments:

RStudio for Question 1 and 3.
Jupyter Notebook or Colab for Question 2.

Acknowledgments
Special thanks to the University of Canterbury for providing the resources and frameworks to complete this assignment. References to official documentation and tutorials for MLR3, scikit-learn, and qicharts2 were instrumental in the implementation.

Contact
For questions or feedback, feel free to open an issue or contact Uditha Iresh Mayadunna.






