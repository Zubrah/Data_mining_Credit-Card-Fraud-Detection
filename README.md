# CREDIT CARD FRAUD DETECTION- DATA MINING

Credit Card Fraud Detection Dataset on Kaggle : https://www.kaggle.com/mlg-ulb/creditcardfraud

The datasets contains transactions made by credit cards in September 2013 by european cardholders.

WHAT TO EXPECT ::::

The dataset contains only numerical input variables which are the result of a PCA transformation.

Due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.

Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Except for the transaction and amount we dont know what the other columns are (due to privacy reasons). The only thing we know, is that those columns that are unknown have been scaled already.

# DEPLOYED DEMO LINK:
LIVE DEMO : https://dm-creditcard-fraud.herokuapp.com






# VIDEO ILLUSTRATION 
VIDE0 - https://www.loom.com/share/53af718f616d4efc99339f85589a838f







# Dataset 
Dataset Link :- https://www.kaggle.com/mlg-ulb/creditcardfraud


# HOW TO CLONE AND RUN:;

1)  First  Create virtualenvironment with following COMMAND:-

        virtualenv venv

 NOTE:- venv is name of name of virtualenvironment. we can give any name which we want.

2) Then Activate venv:-

        venv\Scripts\activate

3) Then Install requirements.txt with following COMMAND:-

        pip install -r requirements.txt


4)  create superuser by following COMMAND in your root directory:-

        python manage.py createsuperuser

5)  Then start your server by typing following COMMAND:-

        python manage.py runserver







    NOTE:- If you are adding some model in models.py or changing something don't forget to make migrations 

        python manage.py makemigrations

    and migrate it to database

        python manage.py migrate


