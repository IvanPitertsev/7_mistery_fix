# Решатель квадратных уравнений

quadratic_eqation.py содержит функцию get_roots (a, b, c) для вычисления корней квадратичного уравнения
с коэффициентами: a, b, c. Вы можете импортировать модуль quadratic_eqation в свой скрипт

# Как использовать

Пример использования:

import quadratic_eqation.py

a = float(input('a = '))
b = float(input('b = '))
c = float(input('c = '))

root1, root2 = quadratic_eqation.get_roots(a, b, c)

if root1 is None:
    print("root1 =  None ")
else:
    print("root1 =  %f " % (root1))

if root2 is None:
    print("root2 =  None " )
else:
    print("root2 =  %f " % (root2))

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
