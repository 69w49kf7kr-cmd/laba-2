# Math formulas
---
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

***Принимает:*** a, b — **int** — длина и ширина прямоугольника

***Пример:*** `area(4, 6) = 24`
```python
def area(a, b):
    return a * b
```
#### Perimeter
***Формула:*** `P = 2(a + b)`

***Принимает:*** a, b — **int** — длина и ширина прямоугольника

***Пример:*** `perimeter(4, 6) = 20`
```python
def perimeter(a, b):
    return 2 * (a + b)
```
---
## Triangle
#### Area
***Формула:*** `S = 0.5 * h * a`

***Принимает:*** a, h — **int** — основание и высота треугольника

***Пример:*** `area(4, 5) = 10`
```python
import math
def area(a, h):
    return  0.5 * h * a
```
#### Perimeter
***Формула:*** `P = a + b + c`

***Принимает:*** a, b, c — **int** — первая вторая и третья сторона треугольника

***Пример:*** `perimeter(3, 4, 5) = 12`
```python
def perimeter(a, b, c):
    return a + b + c
```