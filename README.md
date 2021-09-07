# python-project-template
Template of a Python project with set up pytest, flake8 and black in GitHub Actions

## Create pipenv
To install production environment run:
```
pipenv install
```

### Development environment
To install development environment run:
```
pipenv install --dev
```

### Generate `requirements.txt`
```
pipenv lock -r > requirements.txt
```

## Run pytest
```
pipenv run pytest
```

## Run black
```
pipenv run black .
```