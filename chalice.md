# chalice
To learn chalice ,poetry concept,terraform,ci-cd pipelines . Other concepts of eseye project 

# chalice Basic Commands
To install Chalice, we'll first create and activate a virtual environment in python3.7

```
$ python3 --version

Python 3.7.3

$ python3 -m venv venv37

$ . venv37/bin/activate

$ python3 -m pip install chalice
```

1. How to create new project in chalice ?
```chalice new-project todo-list ```

2. Folder structure of chalice project ?
```
$ sudo tree -a
.
├── app.py
├── .chalice
│   └── config.json
├── .gitignore
└── requirements.txt

1 directory, 4 files
```
==>
app.py --> To write bussiness logic of api's  like ( views.py + urls.py ).

3. How to run chalice project at local ?
==>
todo-list$ chalice local
Serving on | http://127.0.0.1:8000 |











