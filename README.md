# GLUG Website Public Repo
We are using django REST framework for backend api. <br />
And Vue.js for frontend.

---
Use a virtual envionment for installing this, 
i.e `venv` or `pipenv`.
### Install Dependencies

    - python 3.6.x
    - django 2.0.x
    - pillow 5.1.x
    - djangorestframework 3.8.x

For debian based disto, in virtual evironment terminal type
```shell
pip install django djangorestframework pillow
```
### To run the project on local machine
Inside project directory type
```shell
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```

