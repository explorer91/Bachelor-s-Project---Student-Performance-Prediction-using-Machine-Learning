Student Performance Analyzer: An Interactive Python Tool for Predictive Modeling and Visualization

A Python-based machine learning project with a Tkinter GUI that predicts student performance based on study-related features.
 The system allows users to load datasets, visualize trends, train a regression model, and generate predictions for test data.
Features
●	Load training and test datasets (.tsv format)

●	Visualize data using Matplotlib scatter plots

●	Train a simple regression-based prediction model

●	Predict student performance from test data

●	View evaluation metrics (e.g., Mean Absolute Error)

●	User-friendly interface built with Tkinter
Inputs
The system accepts:
●	Training dataset (.tsv) containing:

○	Study hours

○	Preparation time

○	Attendance

○	Exam scores

●	Test dataset (.tsv) for making predictions

●	User actions through the GUI:

○	Load Data

○	Train Model

○	Visualize Data

○	Predict

○	Evaluate
 Outputs
The system generates:
●	Predicted student performance scores

●	Scatter plots (study hours vs exam score)

●	Regression trend lines

●	Evaluation metrics (e.g., MAE)

●	User feedback through popup messages

How It Works
1.	Load the training dataset via the GUI

2.	The system reads and organizes the dataset

3.	A regression model is calculated manually (no external ML libraries)

4.	Matplotlib is used to generate data visualizations

5.	Load a test dataset

6.	The model predicts performance for each student in the test file

7.	The GUI shows evaluation metrics and graphs
Technologies Used
●	Python

●	Tkinter – GUI interface

●	Matplotlib – Data visualization

●	CSV/TSV Parsing – For dataset handling

How to Run
1.	Install Python 3.x

2.	Install required libraries:
pip install matplotlib
Run the project:python project.py
Use the GUI to:
●	Load training data

●	Visualize charts

●	Predict student performance
Conclusion
The Student Performance Predictor integrates GUI development with custom machine learning logic.
 It is ideal for learning ML basics, exploring student data, and understanding real-world prediction workflows.




![Uploading image.png…]()
