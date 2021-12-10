# TEAM-S GradSchoolZero
CSC 32200 Software Engineering Final Project

# The application is a graduate program management system that can be used by Registrars, Instructors, students and visitors in the Graduate School.

`Phase I report:'
`
https://docs.google.com/document/d/1DAu1bj3FWoDtEsOTPkQOJbSO8nXbTuFDSy1ARNMdvVw/edit?usp=sharing


`Phase II report:` https://docs.google.com/document/d/1yz6FoeKtJqNopBGAmZwHEI0rfkARW_sjMqGpyztAHmI/edit?usp=sharing

## Instructions to run the project

1. First create django environment to the local machine

`python3 -m venv env`

2. Activate the environment

### Windows Terminal: 
`env\Scripts\activate`

### gitbash:

`source env Scripts\activate`


### Mac: 
source env/bin/activate 

3. Install the libraries.


`pip install -r requirements.txt`


4. Make migrations

`python manage.py makemigrations`

5. Migrate

`python manage.py migrate`

6. Finally runserver which will provide the link to the web

`python manage.py runserver`

## To handle the register responsibilities

1. For that we have to create SuperUser. In the Windows Terminal, First activate the environment. Then type
 `python manage.py createsuperuser`
It will ask for username and password to activate the superuser duties.

-> You can apply as as instructor or student 
-> After admin accepts new instructor or student, a UUID is given at the top which can be used to make an account for instructor and student 
-> Use your new account credentials to login as student or instructor 
