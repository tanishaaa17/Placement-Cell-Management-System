
# Placement Cell Management System
![David (path)](https://img.shields.io/github/package-json/v/plankanban/planka)  

The Placement Cell Management System permits the Student to login/sign-up into the application and view current job
opportunities available. The System would store all the academic as well as personal details of the
students who wish to be placed and the Companies who offer jobs to the students. Students can
apply for the jobs if they are eligible. The admin can manage the database and post upcoming job or
internship opportunity which can be viewed by the students who are eligible for it. Admin can also
view the Statistics of Current Placement Drive.

## Use case Diagram for Admin

![](https://drive.google.com/uc?export=view&id=1k7Uj3gT8WWLKUqxmDgOpdDFrXL2ONUXG)

## Use case Diagram for Student

![](https://drive.google.com/uc?export=view&id=1WGbVplOH2d4jLUAgo5tU7Then3U5bYUP)

## ER Diagram

![](https://drive.google.com/uc?export=view&id=1OD723ztBDV9PeBr5sL458cqaZXQ_7cXl)

## Schema Diagram

![](https://drive.google.com/uc?export=view&id=19WOQ-9P2KNQTbqCW1lFkDb8B47qaX9uq)



## Installation and Project Startup Guide

Please refer to these links and make sure you have Python, Flask and Postgres installed and working properly on your machine:

* https://linuxize.com/post/how-to-install-flask-on-ubuntu-20-04/
* https://www.digitalocean.com/community/tutorials/how-to-use-a-postgresql-database-in-a-flask-application

Go to your Project Directory.

To run this project type:

```bash
  source venv/bin/activate
```
```bash
  export FLASK_APP=app
```
```bash
  export FLASK_ENV=development
```
```bash
  export DB_USERNAME="tanishaagarwal"
```
Username might vary from user to user so remember you Username.
```bash
  export DB_PASSWORD="password"
```
Password might vary from user to user so remember you Password.
```bash
  flask run
```
If everything worked fine then you should see:

![](https://drive.google.com/uc?export=view&id=1W1C8ITwn6f7QwhmTXD8mj8n35D6hnq-s)

Now Open any browser and type the https link provided in the running server (https://127.0.0.1:5000).


