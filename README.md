# TDD Django Experiments

First experience in Django based on http://www.obeythetestinggoat.com/
The prerequisites are stated here: http://www.obeythetestinggoat.com/book/pre-requisite-installations.html

### Prerequisites
Python version tested is 3.6.5 (pyenv)
Configure a virtualenv:
```(bash)
pyenv install 3.6.5
pyenv virtualenv 3.6.5 my-testing-goat-py
```
Activate a virtualenv:
```(bash)
pyenv shell my-testing-goat-py
pyenv rehash
```
Exit virtualenv:
```(bash)
pyenv deactivate
```

### Concepts and Useful Commands
```(bash)


Running the Django dev server

    python manage.py runserver
Running the functional tests

    python functional_tests.py
Running the unit tests

    python manage.py test
The unit-test/code cycle

        Run the unit tests in the terminal.

        Make a minimal code change in the editor.

        Repeat!


```
