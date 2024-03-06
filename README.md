# Flask (CS50)

> Link - https://www.youtube.com/watch?v=-aqUek49iL8

## Quickstart
```
$ pip install flask
```
A minimal Flask application looks something like this:

```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():
    return "<p>Hello, World!</p>"
```

## Run the application

```
$ flask run
```

> Pull requests are always welcome :) 


