# Решение первой лабы  
## Цель: научиться работать с git 

---

### ход работы
1. копировал репозиторий с удаленного сервера к себе на локальную машину 
`git clone https://github.com/smartiqaorg/geometric_lib`
2. Создал ветку в которой буду работать 
`git switch -c new_features_561009`
3. Добавил файл для прямоугольника - вычисления площади и периметра 
`touch rectangle.py`
4. Еще один файл - для треугольника с теми же вычислениями 
`touch triangle.py`

---


## Math formulas

## Circle
#### Area
***Формула:*** `S = πR²`

***Принимает:*** r — **int** — радиус круга

***Пример:*** `area(5) = 78.54`
```python
import math
def area(r):
    return math.pi * r * r
```
#### Perimeter
***Формула:*** `P = 2πR`

***Принимает:*** r — **int** — радиус круга

***Пример:*** `perimeter(5) = 31.42`
```python
import math
def perimeter(r):
    return 2 * math.pi * r
```
---
## Square
#### Area
***Формула:*** `S = a²`

***Принимает:*** a — **int** — сторона квадрата

***Пример:*** `area(5) = 25`
```python
def area(a):
    return a * a
```
#### Perimeter
***Формула:*** `P = 4a`

***Принимает:*** a — **int** — сторона квадрата

***Пример:*** `perimeter(5) = 20`
```python
def perimeter(a):
    return 4 * a
```
---
## Rectangle
#### Area
***Формула:*** `S = a · b`

***Принимает:*** a — **int** — длина прямоугольника

***Принимает:*** b — **int** — ширина прямоугольника

***Пример:*** `area(4, 6) = 24`
```python
def area(a, b):
    return a * b
```
#### Perimeter
***Формула:*** `P = 2(a + b)`

***Принимает:*** a — **int** — длина  прямоугольника

***Принимает:*** b — **int** — ширина прямоугольника

***Пример:*** `perimeter(4, 6) = 20`
```python
def perimeter(a, b):
    return 2 * (a + b)
```
---
## Triangle
#### Area
***Формула:*** `S = 0.5 * h * a`

***Принимает:*** a — **int** — основание треугольника

***Принимает:*** h — **int** — высота треугольника

***Пример:*** `area(4, 5) = 10`
```python
import math
def area(a, h):
    return  0.5 * h * a
```
#### Perimeter
***Формула:*** `P = a + b + c`

***Принимает:*** a — **int** — первая сторона треугольника

***Принимает:*** b — **int** — вторая сторона треугольника

***Принимает:*** c — **int** — третья сторона треугольника


***Пример:*** `perimeter(3, 4, 5) = 12`
```python
def perimeter(a, b, c):
    return a + b + c
```
---

### Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a
- Triangle P = a + b + c
## история в хэшах:
* 5d49026 changed second mistake - retuen instead of retuen
* 56a904e fixed a problem with a rectangle perimetr calculation
* 3a64bb4 have added new file to the branch
* d078c8d (origin/main, origin/HEAD, main) L-03: Docs added
* 8ba9aeb L-03: Circle and square added
(END)