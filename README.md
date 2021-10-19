# About: Everyone was a [n00b](https://dictionary.cambridge.org/dictionary/english/noob) once ;-)
My first repo on GitHub - a portfolio of some data science projects I undertook as part of the Post Graduate Program in Machine and Deep Learning at IIIT Bangalore. Here's a [link](https://www.iiitb.ac.in/advanced-certificate-programme-in-machine-learning-deep-learning) to the programme in its current avatar (it's Oct '21 now, and the program will likely continue evolving. So, ping me if the link is broken or you need further information!)

# Spotlight
Inside this repo, you'll find evidence of my competence in the following skill set:
- Programming in Python - NumPy, SciKit Learn, Tensorflow (Keras)
- Data Visualisation and Exploratory Data Analysis
- Application of a number of Machine and Deep Learning algorithms to complex datasets
- Interpretation of Model Statistics

# Project (Folder) Descriptions

1. [Exploratory Data Analysis on Lending Club applicants/loans data]()
    - In this project, I visualise and explore Lending Club loans data to uncover relationships between borrower and loan attributes and the likelihood of the loan to go bad (remain unpaid to the lender)
    - The files inside include:
      - The data file (loans.csv)
      - A data dictionary file (Data_Dictionary.xlsx)
      - A Jupyter notebook with visualisations and analysis, and
      - A PDF presentation with key insights
 
2. [Regression - Car Price Prediction]()
    - In this project, a new car manufacturer wants to enter a market with multiple existing placers and wishes to understand how best to price its cars. Made available is data covering the price and features of several different cars in the market
    - The files inside include:
      - The data file (CarPrice_Assignment.csv),
      - A data dictionary file (Data Dictionary - carprices.xlsx), and
      - A Jupyter notebook covering some intricate exploratory data analysis and a suite of OLS regression models

3. [Classification - Telecom Churn Prediction and Factor Analysis]()
    - In this project, a telecom services providers wants to predict which of its customers are likely to churn and also understand what factors influence churn, so as to take preventive action. The service provider has data covering the customer behaviour over a four month period
    - A particularly important consideration: the dataset in this project consists of 99,999 observations of __226__ variables
    - For classification, I reduce the original dataset into a subset of principle components (PCA), take care of class imbalance (via under-sampling), and run a variety of different classification algorithms on the transformed dataset:
      -  Logistic Regression, 
      -  Random Forest, 
      -  Extreme Gradient Boosting (XGBoost), 
      -  Linear and Non-Linear Support Vector Machines
    - For factor analysis, I develop a separate logistic regression model using pre-transformed data allows for an __explainable__ factor analysis
    - Apart from the Jupyter notebook that covers the above-mentioned tasks, files included in this folder are:
      - The data file (telecom_churn_data.csv), and
      - A data dictionary file (Data+Dictionary-+Telecom+Churn+Case+Study.xlsx)

4. [Multi-Class Classification of Hand Gestures in Videos]()
    - In this project, a manufacturer of Smart TVs wishes to introduce a new product feature whereby a TV sensor captures and processses its user's hand gestures in real time for certain remote control tasks. Given a labelled training dataset consisting of over 650 videos (each video consisting of a sequence of 30 images) of human hand gestures, my task was to develop a model that learns to predict the correct label corresponding to a new hand gesture video
    - I was able to train a model delivering 67% accuracy on a validation dataset consisting of 100 videos using a 3D-Convolutional Neural Network (3D-CNN)
    - The files inside this folder include:
      - A sub-folder consisting of both training and validation videos and labels,
      - A Jupyter notebook covering data (image) pre-processing steps, batch generation steps, model (3D-CNN) construction and fitting steps (Keras),
      - A copy of the model with best hyperparameters I encountered (best_model.h5), and
      - Some notes on architectural decisions (some_notes.pdf)
