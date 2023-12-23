# Django Poll Application 

## Overview

This is a simple Django Polls application enabling users to participate in voting on various poll questions, comprising a public site for viewing and voting on polls, as well as an admin site facilitating the addition, modification, and deletion of polls.

## Libraries and Frameworks:

These are the libraries and frameworks used to build this chat application.
1.Django == 4.2.7

## username: Admin Password: Admin123
[![admin.png](https://i.postimg.cc/xT3L4yGP/admin.png)](https://postimg.cc/Yhj44Fs4)

## Getting started with project
First clone the repository from Github and cd into poll-application

```bash
$ git clone https://github.com/maripfonde/poll-application.git
$ cd poll-application
```

Activate the virtual environment for the project
```bash
$ python3 -m venv poll-env
$ source poll-env/bin/activate

Windows users
> poll-env\Scripts\activate
```

Install project dependencies 
```bash
$ pip install -r requirements.txt
```

Then aplly the migrations 
```bash
$ python manage.py migrate
```

Now you can run the server
```bash
$ python manage.py runserver
```

## Running tests and debugging
```bash
$ python manage.py test polls
```
