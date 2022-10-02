<!-- Please update value in the {}  -->

<h1 align="center">Django Quiz App</h1>

<div align="center">
  <h3> 
    <a href="https://github.com/esadakman/django-quiz-app">
      Project
    </a> 
  </h3>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Acknowledgements](#acknowledgements)
- [Overview](#overview)
- [Built With](#built-with)
- [Project Structure](#project-structure)
- [How to use](#how-to-use)
- [Contact](#contact)


## Acknowledgements

- I created a Quiz Application with Django Rest Framework that allows users to
    - register/login/logout
    - View quizzes and questions
    - CRUD quizzes and questions(stuff only)

<!-- OVERVIEW -->
## Overview

![quiz-app](https://user-images.githubusercontent.com/98649983/193446823-9fb4ca0e-b84e-4d77-9508-4a86ef0b69ee.gif)



### Built With

<!-- This section should list any major frameworks that you built your project using. Here are a few examples.-->

- Django
- Django Rest Framework
- Django Rest Auth
- Django Nested Admin

## Project Structure

```bash
.──── django-quiz-app (repo)
│
├── main
│     ├── __pycache__ 
│     ├── __init__.py 
│     ├── asgi.py
│     ├── urls.py
│     ├── wsgi.py
│     └── settings.py
│─── quiz
│       ├── __pycache__
│       ├── migrations
│       │── __init__.py
│       ├── admin.py
│       ├── apps.py
│       ├── models.py  
│       ├── serializers.py 
│       ├── tests.py
│       ├── urls.py
│       └── views.py 
├── manage.py
├── db.sqlite3 
├── requirements.txt
└── .env

```

## How To Use 

To clone and run this application, you'll need [Git](https://git-scm.com)

```bash
# Clone this repository
$ git clone https://github.com/esadakman/django-quiz-app 

# Install dependencies
    $ python -m venv env
    $ env/Scripts/activate (for win OS)
    $ source env/bin/activate (for macOs/linux OS)
    $ pip install -r requirements.txt 

# Add .env file for secret key 

- After these you can run the project as usual => 

# Run the app
    $ python manage.py runserver
```

## Contact

- Website [@esadakman](https://esadakman.github.io/)
- GitHub [@esadakman](https://github.com/esadakman)
- Linkedin [@esadakman](https://www.linkedin.com/in/esadakman/)

 