# Pyramid tutorial

[Todo list app in one file](https://docs.pylonsproject.org/projects/pyramid_cookbook/en/latest/sample_applications/single_file_tasks.html)

## Install dependencies

- Install Python3, check the version:
```
python3 --version
Python 3.6
```

- Create a virtual environment to install Python libraries needed:
```bash
python3 -m venv venv
# activate your virtual environment
source venv/bin/activate
# install all requirements
pip install -r requirements.txt
```

## Run the webapp

```bash
source venv/bin/activate
python webapp/tasks/tasks.py
```

Go to http://localhost:8080/
