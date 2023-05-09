# Ajay-Vijendran-G_21BAI1202

ArtiFinance is a simple ML integrated web-based Chatbot which will predict your eligibility for a loan by asking you a series of questions

This is made with the help of Dialogflow(A NLP platform to create user interactive chatbots) and Flask(A python based microframework)

# Check it out here: https://artifinance.onrender.com

# WorkFlow:
1) DialogFlow Bot gets the details from user and sends it to Flask with the help of HTTP requests

2) The data undergoes some preprocessing and is fed to a pre-trained model.

3) The model is made with the help of Random Forest Classifier algorithm on a dataset from [Kaggle](https://www.kaggle.com/datasets/subhamjain/loan-prediction-based-on-customer-behavior?select=Training+Data.csv)

4) The result from the model is sent to the Bot in Json format and the Bot Displays the result

# How to run?
1.Fork/Clone/Download this repository

```
git clone https://github.com/AjayVijendran/ArtiFinance---The-future-of-loans.git
```

2. Install virtualenv:

 ```
 pip install virtualenv
 ```

2. Open a terminal in the project root directory and run:

  ```
  virtualenv env
  ```

4. Then run the command:

```
.\env\Scripts\activate
```

5. Then install the dependencies:

```
(env) pip install -r requirements.txt
```

6. Finally start the web server:

```
(env) python app.py
```
# Deployment
This web app is deployed on [Render](https://render.com/), a great alternative to Heroku

Render is a unified cloud to build and run all your apps and websites with free TLS certificates, global CDN, private networks and auto deploys from Git.
