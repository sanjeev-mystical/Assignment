# Assignment
# Prerequesties
python >= 3.7

node js

# Backend Side
for Backend first create the virtual enviornment and then activate it. Install the mentioned dependencies in requirement.text.

# Commands
# For running the django server
python manage.py runserver

# For migrations
Python manage.py makemigrations

python manage.py migrate

# For running the scrapping service
If u have redis server installed in the use the celery otherwise use the python script in the backend folder.

# For Celery
# Go to backend folder and then use this - 
celery -A assignment beat -l info

celery -A assignment worker -l info --pool=solo

# if you do not have redis server then try the Scrapping_script.py
python Scrapping_script.py

# For react
Run these commands inside the frontend folder

# For Start the react app
npm run start

# For creating the build
npm run build

# For installing the dependencies
npm i
