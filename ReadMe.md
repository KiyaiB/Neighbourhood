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
#### Run the Application
  
  python3 manage.py runserver

#### Testing the Application
   
   python3 manage.py test

Open the Application in your browser

## Technology used
* [Python3.8](https://www.python.org/)
* [Django==3.2.7](https://docs.djangoproject.com/en/2.2/)
* [Heroku](https://heroku.com)
## Known Bugs
* There are no known bugs
## Support and contact details
For more information,comments or clarification contact on clara.metto@student.moringaschool.com
### License
*MIT License*
Copyright (c) 2022 Babra Kiyai

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Copyright (c) {2022} **Babra Kiyai**



