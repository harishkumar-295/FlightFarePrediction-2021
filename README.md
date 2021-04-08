# FlightFarePrediction-2021

This is an end to end project for predicting flight fare and deploying the model using and in heroku platform.

The link of the deployed app : https://flight-fare-prediction-2021.herokuapp.com

![Screenshot (103)](https://user-images.githubusercontent.com/80705710/111488840-a122fe00-875f-11eb-8098-80979dc757eb.png)

# Overview

This is a Flask web app which predicts fare of Flight ticket.

# Motivation

I started to learn different Machine Learning model to understand it and get most out of it by applying to real world problems. I understood the mathematics behind all supervised models i.e for this problem problem I used a Regression model. Finally I applied it this problem.

# Installation
The Code is written in Python 3.6. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

pip install -r requirements.txt

# Deployement on Heroku

Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.
You can Login/Signup using the link: https://id.heroku.com/login

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_price.ipynb
├── flight_rf.pkl
├── requirements.txt
```


# Technologies used
 1. Flask
 2. Gunicorn
 3. Scikit-Learn

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 
 
# Future Scope
 1.Use multiple Algorithms to find a better algorithm with better performance.
 
 2.Optimize Flask app.py
 
 3.Improve the Front-End to make the app look more attractive and interactive.
