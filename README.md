<span align="center">
<h1>VIT-HACK-2020</h1>
<h3>Covinfo - Healthcare theme</h3>
</span>

# Covinfo
Our Project is a one stop for getting all the information about the Ongoing Pandemic COVID-19. We have made a made a minimalistic User Interface with
many the features like : 

1. Latest Notifications and Updates
2. Total Number of beds and hospitals in rural and urban areas with state wise analysis.
3. Included the Statistics in the form of charts to provide user, the ease of visualizing the relevant data.
4. Helpline number for each of the states.

We have fetched the APIs and printed the data in a sortable format giving the user to filter according to his need and further we have also trained the provided data to predict the missing values in it and then plotted the final comparison graph.

For data scientists, handling missing data is an important part of the data cleaning and model development process. Often times, real data contains
multiple sparse fields or fields that are laden with bad values. In this project, we have built models that can be used to impute missing or bad values in data.
When the data set is analysed we face with a problem of missing data in ageEstimate and redundant data in various labels which may impact our
processing of the data.
Pre-processing is done to sort out the data by removing the redundant data and performing encoding on the categorical data to establish a metrics from where
we can decide on a filter which we can use it to predict the missing data. After the data is processed we correlate the data against each other to find
similarity.
First let’s consider building a model that imputes missing ‘ageEstimate’ values using the ‘status’. To start, let’s correlate between ‘ageEstimate’ and ‘status’. We
see that there is a weak correlation. Let’s build a linear regression model that uses ‘status’ to predict the ‘ageEstimate’. First, let’s import the ‘Linear
Regression’ module from ‘scikit-learn’. Now let’s evaluate the performance of our model. Let’s use mean squared error to evaluate the performance of our model. 
For comparison purposes we use various other models like Random Forests Regression, but in this scenario we had best possible predictions with Linear Regression.

#### The process goes thus:
Call the variable where you have missing values as y.
Split data into sets with missing values and without missing values, name the
missing set X_text and the one without missing values X_train and take y
(variable or feature where there is missing values) off the second set, naming it
y_train.
Use one of classification methods to predict y_pred.
Add it to X_test as your y_test column. Then combine sets together.
Further improvements can be done on this like hyperparameter tuning, and
using a deep learning based network model which is explicitly designed for this.

## Tech Stack Used

### WEB DEVELOPMENT
<img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white" /> <img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white" /> <img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" /> <img src="https://img.shields.io/badge/jquery%20-%230769AD.svg?&style=for-the-badge&logo=jquery&logoColor=white" /> <img src="https://img.shields.io/badge/django%20-%23092E20.svg?&style=for-the-badge&logo=django&logoColor=white" />

### MACHINE LEARNING
- Linear Regression Model
- Random Forests Model
- Pandas Pipeline

## Instructions to run the project

To run the project please install the following libraries:
1. Install Django
```
pip install django
```

2. Install Django Rest Framework
```
pip install djangorestframework
```

3. Install Pandas
```
pip install pandas
```

4. Run server
```
 python manage.py runserver
```

## Hosted Link:
http://akshatgupta1903.pythonanywhere.com/api/

## Credits
- Team Name: index.html
- Saksham Madan
- Yogeswari Sahu
- Shubh Naresh Gupta
- Akshat Gupta

