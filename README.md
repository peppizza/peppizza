```py
from datetime import datetime

class Readme:
    def __init__(self):
        self.tech_stack = ['Python', 'Flask', 'Reactjs', 'Go']
        self.started_programming = datetime(year=2020, month=3, day=4)
        self.age = 15
        self.gender = 'male'
        self.tools = ['VSCode', 'Vim', 'Git']

        self.contacts = {
            'Discord': 'Le baguette man#9289'
            # TODO: get more contacts
        }

    def can_i_do_it(self, complexity: int) -> bool:
        if complexity > 4:
            return False
        else:
            return True

Readme()
```
