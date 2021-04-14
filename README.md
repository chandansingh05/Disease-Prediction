# Disease-Prediction
# Multiple Disease Predictor
## About
This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:
* Diabetes
* Breast Cancer
* Heart Disease
* Kidney Disease
* Liver Disease
* Malaria
* Pneumonia

## Models with their Accuracy of Prediction
Disease | Type of Model | Accuracy
--- | --- | ---
Diabetes | Machine Learning Model | 95.25%
Breast Cancer | Machine Learning Model | 96.25%
Heart Disease | Machine Learning Model | 85.25%
Kidney Disease | Machine Learning Model | 99%
Liver Disease | Machine Learning Model | 77%
Malaria | Deep Learning Model(CNN) | 96%
Pneumonia | Deep Learning Model(CNN) | 95%

## NOTE
==> You can access the website live at: # <br>
==> Python version 3.6.8 was used for the whole project.<br>


## Steps to run the WebApp in local Computer
**Step-1:** Download the files in the repository.<br>
**Step-2:** Get into the downloaded folder, open command prompt in that directory and install all the dependencies using following command<br>
```python
pip install -r requirements.txt
```
**Step-3:** After successfull installation of all the dependencies, run the following command<br>
```python
python app.py
```
## 
## Dataset Links
All the datasets were used from kaggle.
* [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
* [Breast Cancer Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
* [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
* [Kidney Disease Dataset](https://www.kaggle.com/mansoordaku/ckdisease)
* [Liver Disease Dataset](https://www.kaggle.com/uciml/indian-liver-patient-records)
* [Malaria Dataset](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria)
* [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)


