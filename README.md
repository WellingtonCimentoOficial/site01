# site01

* First clone this repository with command "git clone https://github.com/WellingtonCimentoOficial/site01.git" and enter the folder with command "cd site01"
* replace in the project these words with your informations: EDITAR,YOURKEY and YOURID
* rename the .env-example to .env and fill in the fields
* Create virtual enviroment with command "python -m venv venv"
* Enable virtual environment with command in windows "venv\Scripts\activate" in linux "venv/bin/activate"
* Install all requirements with command "pip install -r requirements.txt"
* Make all migrations with command "python manage.py makemigrations&&python manage.py migrate"
* Create super user with command "python manage.py createsuperuser"
* Run django with command "python manage.py runserver"
* Access url http://127.0.0.1:8000/accounts/dashboard/admin in your browser and sign with your credentials after click in "Subscriptions" and create a new subscription with name "FREE" and save
