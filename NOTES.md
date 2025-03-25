
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
export FLASK_APP=./src/details/app.py -> to run app with flask run
pip3 freeze > requirements.txt
/opt/homebrew/bin/python3 /Users/nataliastasiukova/Desktop/DevOps/Python/python_class_task_hw/src/srv/app.py
pip install watchdog -> to detect focus changes and restart Flask

- run app
python3 src/details/app.py
or: flask run
or: flask --debug run