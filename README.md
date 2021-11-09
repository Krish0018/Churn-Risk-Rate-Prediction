# Churn-Risk-Rate-Prediction

### About the project
In this project, I tried to find out out a company will lose or retain its customers on the basis of detail, feedback, complain and other things.


### Tool Used
Used Python for data analysis for that particular dataset. Libraries used for this project are:
Numpy
Pandas
Matplotlib
Seaborn
sklearn

### Installation
for numpy
```pip install numpy```


for Pandas
```pip install pandas```


For Matplotlib
```pip install matplotlib```


For Seaborn
```pip install seaborn```

For Sklearn
```pip install scikit-learn```



### Key Insights

Find out a special character information in one feature

<img width="600" alt="f1" src="https://user-images.githubusercontent.com/69238621/140895027-47f40bf8-2459-4ce8-ad52-7b615234da42.PNG">

This could be replace by any other value. As it was a categorical feature so I filled it with mode.


To found out the relation between the independent continous feayres and the target lable used correlation and showed it with the help of heatmap.

<img width="600" alt="f2" src="https://user-images.githubusercontent.com/69238621/140895388-843fb347-c2a2-4636-9293-e4223d2db0fb.PNG">

Then after used feature engineering.
standardised the data using Standard scaler.
And used some algorithms for training and also used hyperparmeter tuning.
Finalised the model on the basis of overall performance and used it on train data.
