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


## [Math formulas](/Users/chelowedik/Desktop/programming/geometric_lib/docs/explain.md)


### Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²
- Triangle S = 0.5 * h * a

---

### Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a
- Triangle P = a + b + c
## [история в хэшах](/Users/chelowedik/Desktop/programming/geometric_lib/docs/history.md):
* 5d49026 changed second mistake - retuen instead of retuen
* 56a904e fixed a problem with a rectangle perimetr calculation
* 3a64bb4 have added new file to the branch
* d078c8d (origin/main, origin/HEAD, main) L-03: Docs added
* 8ba9aeb L-03: Circle and square added
(END)