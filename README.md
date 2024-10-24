<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="assets/benz-python.jpg" alt="Project logo"></a>
</p>

<h3 align="center">Mercedes-Benz Greener Manufacturing Kaggle Competition</h3>

---

<p align="center">
This dataset contains an anonymized set of variables, each representing a custom feature in a Mercedes car. For example, a variable could be 4WD, added air suspension, or a head-up display. The ground truth is labeled ‘y’ and represents the time (in seconds) that the car took to pass testing for each variable.
</p>
<p align="center">Competition Link: https://www.kaggle.com/competitions/mercedes-benz-greener-manufacturing/data</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

We’re a team of five data enthusiasts from the Luther College Data Science Club, working together on a practice competition. Each of us brings something unique to the table: from exploratory data analysis (EDA) and dimension reduction to evaluation and visualization, we’ve got all the bases covered.

Our goal is to sharpen our skills, tackle complex datasets, and turn insights into action. We work hard, learn fast, and enjoy every step of the process—because to us, data isn’t just numbers, it’s a story waiting to be told.

## ⛏️ Built Using <a name = "built_using"></a>

- [Pandas](https://www.mongodb.com/) - Data Model and Access
- [Numpy](https://expressjs.com/) - Low Level Array's
- [Sckit-Learn](https://vuejs.org/) - ML Tooling and Models

## ✍️ Authors <a name = "authors"></a>
- [@nguyhu01](https://github.com/nguyhu01) - Project Lead
- [@vincent-buchner](https://github.com/vincent-buchner) - Modeling
- [@SorenBasnet](https://github.com/SorenBasnet) - Dim. Reduction
- [@Drewni01](https://github.com/Drewni01) - Visualization
- [@dieple-ldnd](https://github.com/dieple-ldnd) - EDA


<!-- ## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References -->
## 📝 Style Guide

### 1. General Naming Conventions
#### 1.1 Variables and Function Names
- Variables and functions should be named using `snake_case`.
  ```python
  my_variable = 10
  def my_function():
      pass
#### 1.2 Class Names
- Classes should be named using PascalCase.
```python
class MyClass:
    pass
```
#### 1.3 Class Methods
- Class methods should be named with the first letter capitalized (CapitalCamelCase).
```python
class MyClass:
    def MethodOne(self):
        pass
    
    def MethodTwo(self, value):
        pass
```
#### 1.4 Constants
- Constants should be written in all uppercase letters with underscores separating words.
```python
MAX_LIMIT = 100
```

### 2. Code Layout and Formatting
#### 2.1 Indentation
- Use 4 spaces per indentation level. Do not use tabs.
#### 2.2 Maximum Line Length
- Limit all lines to a maximum of 79 characters.

#### 2.3 Blank Lines
- Use 2 blank lines to separate top-level functions and class definitions.
- Use 1 blank line inside functions and methods to separate logical sections of code.

#### 2.4 Imports
- Imports should be on separate lines and grouped in the following order:
    - Standard library imports
    - Related third-party imports
    - Local application imports

Each group should be separated by a blank line.
```python
import os
import sys

import requests

from my_module import MyClass
```
### 3. Docstrings and Comments
#### 3.1 Docstrings
- Use docstrings for all public modules, functions, classes, and methods. Use triple double quotes (""").
``` python
def my_function():
    """This function does something."""
    pass
```

#### 3.2 Comments
- Use comments sparingly. Prefer code that explains itself. When needed, use # for single-line comments.
```python
# This is a comment
x = x + 1  # Increment x by 1
```
### 4. Classes and Object-Oriented Programming
#### 4.1 Class Definition
- Define each class in its own module unless the classes are closely related.
- Inherit from object explicitly for compatibility with Python 3.x.
```python
class MyClass(object):
    def __init__(self):
        self.attribute = 1
```

#### 4.2 Class Method Names
- Follow the CapitalCamelCase method naming convention:
```python
class Vehicle:
    def Start(self):
        pass
    
    def Stop(self):
        pass
```
#### 4.3 Private Methods and Variables
- Private methods and variables should start with a single underscore.
```python
class MyClass:
    def _private_method(self):
        pass
```

### 5. Type Hints and Annotations
- Use type hints to indicate expected types for function arguments and return values.
```python
def greet(name: str) -> str:
    return f"Hello, {name}"
```


