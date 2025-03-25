
# Step 1

- linux setup
install pipenv
vi ~/.bash
export PATH=$PATH:$HOME/.local/bin
pipenv init / pipenv shell

- mac setup
python3 -m venv .
source bin/activate
pip3 install pipenv
pip3 install flask

- optional
export FLASK_APP=./src/details/app.py
pip3 freeze > requirements.txt
/opt/homebrew/bin/python3 /Users/nataliastasiukova/Desktop/DevOps/Python/python_class_task_hw/src/srv/app.py

- run app
python3 src/details/app.py
or: flask run