# FinalProject4

## About this project:

## Approach
=======
![Alt Text](https://media.giphy.com/media/fp0MsYYaQQtQtCJXxr/giphy.gif)

## About this project:
To build a patient prognosis tool. Simply input symptoms and machine learning will do the heavy lifting to predict a prognosis.

## Approach
(1) Training and Test CSV data stored in AWS.\
(2) Training and Test CSV data imported into Jupyter notebook where ETL is performed on Pandas dataframes.\
(3) ML is done on Training and Test dataframes in Jupyter.\
(4) An html survey collects 'real' patient data in JSON form.\
(5) That 'real' JSON data is then uploaded to MongoDB.\
(6) GitBash is used to export 'real' data from MongoDB in CSV form.\
(7) CSV of 'real' data imported into original Jupyter notebook.\
(8) Lastly, 'real' patient data is fed to the ML model and a prediction is made.\
Note: in step 6 rather than the in-built export feature in MongoDB, it's because it gets around the alphabetisation of columns that I messaged you about the other day. The code we use specifies the column order so that it exports exactly as we want it.
>>>>>>> 789ee4b83ec1b7d344e3274b4ae2a01f3cfeabe1

## **Architectural Diagram:**
HTML Input Form → JSON Output → Flask API → Import API using Python → Run Python Script → Machine Learning Prediction & Output

## **Data Sources:**
<<<<<<< HEAD
=======
Data is derived from Kaggle. Data spans 2016 till 2021. ***
- [ABS employee earnings](https://www.abs.gov.au/statistics/labour/earnings-and-working-conditions/employee-earnings-and-hours-australia/may-2021#data-download)

## **Coding Languages:**

## **Data Bases:**

## **Platform:**

## **IDE:**

## **Limitations, Assumptions & Challenges:**

## **Visualizations & Analysis:**

## **Observations:**

## **Website Design:**
=======
- Interpretations of symptoms
- Recommend Doctor to complete the form on behalf of patient
- Only set prognosis predicted e.g. no mental health prognosis 

## **Observations:**
97% Machine Learning accuracy in predicting prognosis based on 132 input symptoms

## **Output Design:**
This application includes input webpage with intent to provide prognosis output using HTML, Python, and Machine Learning.

## **Project Authors:**
Authors:

Vik Shah - https://github.com/viktiger

Chris Burley - https://github.com/DizzyBurls

Jarrod Casey - https://github.com/JarrodCasey

Tu Cam - https://github.com/tucamdang

Navid Mortagh - https://github.com/amir-motlagh

