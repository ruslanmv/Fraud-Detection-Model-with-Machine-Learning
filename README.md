# How to build a Fraud Detection Model with Machine Learning

Hello, today we are going to create a machine learning model to detect frauds.



# Step 1. Installation of Conda

First you need to install anaconda at this [link](https://www.anaconda.com/products/individual)

![png](assets/images/posts/README/1-16601652164621.jpg)

in this location **C:\Anaconda3** , then you, check that your terminal , recognize **conda**

```
C:\conda --version
conda 23.1.0
```

# Step 2. Environment creation

The environments supported that I will consider is Python 3.8,

I will create an environment called **detector**, but you can put the name that you like.

```
conda create -n detector python==3.8
```

then we activate

```
conda activate detector
```

then in your terminal type the following commands:

```
conda install ipykernel
```

then

```
python -m ipykernel install --user --name detector --display-name "Python (Fraud Detector)"
```

then we install the 

```
pip install pandas numpy xgboost scikit-learn imblearn streamlit matplotlib seaborn shap
```

