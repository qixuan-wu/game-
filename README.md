Game Data with Python and Flask
1.creat environment
 1.pyenv local 3.7.0 # this sets the local version of 
 2.python to 3.7.0python3 -m venv .venv # this creates the virtual environment for you
 3.source .venv/bin/activate # this activates the virtual environment
 4.pip install --upgrade pip # package installer for python
 5.pip install Faker
2.	open web
  1.cd 文件名
  2.export FLASK_APP=story.py
  3.export FLASK_ENV=development
	4.python -m flask run -h 0.0.0.0
