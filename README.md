# mo
# Домашнее задание к лекции 1.«Import. Module. Package»

1. Разработать **структуру** программы "Бухгалтерия". 
- main.py;  
- директория application:  
-- salary.py;  
-- директория db:  
\--- people.py;  
main.py - основной модуль для запуска программы.  
В модуле salary.py функция calculate_salary.  
В модуле people.py функция get_employees.  

2. Импортировать функции в модуль main.py и вызывать эти функции в конструкции.
```
if __name__ == '__main__':
```
**Сами функции реализовать не надо**. Достаточно добавить туда какой-либо вывод.

3. Познакомиться с модулем [datetime](https://pythonworld.ru/moduli/modul-datetime.html). 
При вызове функций модуля main.py выводить текущую дату.

\*4. Создать рядом с файлом main.py модуль dirty_main.py и импортировать все функции с помощью
конструкции (необязательное задание)
```
from package import *
```

---
Домашнее задание сдается ссылкой на репозиторий [BitBucket](https://bitbucket.org/) или [GitHub](https://github.com/)age
