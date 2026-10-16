# **Geometric_lib**

## **Примененные математические формулы**

### Площадь
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²
- Triangle: S = (a*h)/2

### Периметр
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a
- Triangle: P = a + b + c


## **Описание функций**

### 1. Круг (circle.py)

*   **`area(r)`** : Вычисляет площадь круга по его радиусу r.
    ```python
    import circle
    print(circle.area(3))

    >>> 28.274333882308138
    ```
*   **`perimeter(r)`** : Вычисляет периметр (длину окружности) круга по его радиусу r.
    ```python
    import circle
    print(circle.perimeter(3))

    >>> 18.84955592153876
    ```

### 2. Прямоугольник (rectangle.py)

*   **`area(a, b)`** : Вычисляет площадь прямоугольника по его сторонам a и b.
    ```python
    import rectangle
    print(rectangle.area(4, 6))

    >>> 24
    ```
*   **`perimeter(a, b)`** : Вычисляет периметр прямоугольника по его сторонам a и b.
    ```python
    import rectangle
    print(rectangle.perimeter(4, 6))

    >>> 20
    ```

### 3. Квадрат (square.py)

*   **`area(a)`** : Вычисляет площадь квадрата по его стороне a.
    ```python
    import square
    print(square.area(5))

    >>> 25
    ```
*   **`perimeter(a)`** : Вычисляет периметр квадрата по его стороне a.
    ```python
    import square
    print(square.perimeter(5))

    >>> 20
    ```

### 4. Треугольник (triangle.py)

*   `area(a, h)` : Вычисляет площадь треугольника по его основанию a и высоте h.
    ```python
    import triangle
    print(triangle.area(4, 5))

    >>> 10.0
    ```
*   **`perimeter(a, b, c)`** : Вычисляет периметр треугольника по его трем сторонам a, b и c.
    ```python
    import triangle
    print(triangle.perimeter(3, 4, 5))

    >>> 12
    ```


## **История изменения проекта**

*   **`458cc93`**: Исправлена ошибка в вычислении периметра в файле rectangle.py
*   **`a400719`**: Добавлен файл triangle.py
*   **`5d69e6e`**: Добавлен файл rectangle.py
