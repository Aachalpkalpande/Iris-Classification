web: python deploy.py
click==8.1.6
Flask
Jinja2==3.1.2
joblib==1.3.1
numpy==1.21.6
scikit-learn


# Iris Classification
Iris classification is a typical machine learning classification project where we use a dataset to train the module to identify/recognise the target. There are three species of Iris flower. When a new flower is given, we need to predict it belongs to which type. Following figure shows the samples of all three species
![Iris_Type.jpg](attachment:Iris_Type.jpg)
we don't have to use image processing. Some numeric measurements are given in the dataset that will help the module to classify.

Iris_Measure.png](attachment:Iris_Measure.png)

!pip install scikit-learn==1.3.0

Requirement already satisfied: scikit-learn==1.3.0 in c:\programdata\anaconda3\lib\site-packages (1.3.0)
Requirement already satisfied: scipy>=1.5.0 in c:\programdata\anaconda3\lib\site-packages (from scikit-learn==1.3.0) (1.7.3)
Requirement already satisfied: numpy>=1.17.3 in c:\programdata\anaconda3\lib\site-packages (from scikit-learn==1.3.0) (1.21.5)
Requirement already satisfied: threadpoolctl>=2.0.0 in c:\programdata\anaconda3\lib\site-packages (from scikit-learn==1.3.0) (2.2.0)
Requirement already satisfied: joblib>=1.1.1 in c:\programdata\anaconda3\lib\site-packages (from scikit-learn==1.3.0) (1.3.1)
