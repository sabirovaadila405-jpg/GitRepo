import math

def triangle_area(a, b, c):
    p = (a + b + c) / 2
    area = math.sqrt(p * (p - a) * (p - b) * (p - c))
    return area

# Запрашиваем у пользователя стороны
a = float(input("Введите сторону a: "))
b = float(input("Введите сторону b: "))
c = float(input("Введите сторону c: "))

# Вычисляем площадь
area = triangle_area(a, b, c)

# Выводим результат
print(f"Площадь треугольника: {area}")
