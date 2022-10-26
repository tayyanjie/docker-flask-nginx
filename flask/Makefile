install:
	python3 -m pip install --upgrade pip
	pip3 install -r requirements.txt

format:
	black *.py

lint:
	pylint --disable=R,C *.py
	pylint *.py

test:
	python -m pytest -vv test.py

all: install lint test
