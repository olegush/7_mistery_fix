# Скрипт решения квадратных уравнений

Скрипт решает квадратные уравнения. Тестируется с помощью модуля **unittest**

## Как использовать

Для использования решателя в скрипт **tests.py** из модуля **quadratic_equation** импортируется функция  **get_roots** 

```
from quadratic_equation import get_roots
```

далее с помощью встроенного модуля unittest проводится 4 теста с разными коэффициентами на предмет проверки корней уравнения

```
root1, root2 = get_roots(1, -2, 1)
```

вывод  результата можно организовать, добавив

```

print (get_roots(a, b, c))

```

где a, b, c - коэффициенты квадратного уравнения 


## Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

## Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
