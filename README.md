## Salary Calculation Program

This program is designed to calculate employee salaries and retrieve a list of employees.

### Requirements
- Python 3.x

### Usage
1. Import the necessary functions:

from application.salary import *
from application.db.people import *

2. Run the program:

if __name__ == 'main':
    print("Current date:", datetime.date.today())
    calculate_salary()
    get_employees()

### Project Structure
- application/
  - salary.py
    - calculate_salary()
  - db/
    - people.py
      - get_employees()



## Программа для вычисления заработной платы сотрудников

Данная программа предназначена для вычисления заработной платы сотрудников, а также получения списка сотрудников.

### Требования
- Python 3.x

### Использование
1. Импортировать необходимые функции:

from application.salary import *
from application.db.people import *

2. Запустить программу:

if __name__ == 'main':
    print("Current date:", datetime.date.today())
    calculate_salary()
    get_employees()

### Структура проекта
- application/
  - salary.py
    - calculate_salary()
  - db/
    - people.py
      - get_employees()

