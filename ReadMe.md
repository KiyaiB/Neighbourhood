## NEIGHBOURHOOD

## Author
     Babra Kiyai

## Description
Neighbourhood project is a web application that allows you to be in the loop about what's happening in your neighbourhood.The users are able to set up a profile about them and their location/neighborhood name,They can find a list of different businesses in the neighbourhood, contact information and also create posts.

## User Stories
* Sign in to the application
* Set up a profile about a users neighborhood name
* Find a list of businesses in the neighborhood
* Create posts visible to everyone in my neighborhood
* Change neighbourhood if a user moves
* Only view details of a single neighborhood

## Setup and Installations

##### Clone the repo:


#### Navigate to the requirements folder and install

      cd neighbourhood pip install -r requirements.txt

#### Install and Activate Virtual environment
    
    -python3 -m venv virtual - source virtual/bin/activate

#### Install Dependencies
    
    pip install requirements.txt

#### Setup Database

    SetUp your database User,Password, Host then make migrate
 ```bash
python manage.py makemigrations hood
 ```
 Now Migrate
 ```bash
 python manage.py migrate
```  



