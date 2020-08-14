```py
from flask import Flask

app = Flask(__name__)

@app.route('/')
def index():
    return "https://github.com/peppizza/peppizza"

@app.route('/skills')
def skills():
    return {'skills': ['flask', 'python', 'Go', 'ReactJS']}

@app.route('/about')
def about():
    return {'age': 15, 'gender': 'male', 
    'contact': {'discord': 'Le baguette man#9289'}, 
    'tools': ['VSCode', 'Vim', 'Git']}

app.run()
```
