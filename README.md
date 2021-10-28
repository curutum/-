# Вариант 9

### Задание 1(9) ' Begin 9 Даны два неотрицательных числа a и b. Найти их среднее геометрическое, то есть квадратный корень из их произведения: (a·b)^1/2 '
     
     import random
     import math
     a = random.randrange(1,10)
     b = random.randrange(1,10)
     print("a = ", a)
     print("b = ", b)
     print("Среднее геометрическое: ", math.sqrt(a*b))

### Задание 2(9) ' Integer 9 Дано трехзначное число. Используя одну операцию деления нацело, вывести первую цифру данного числа (сотни) '
   
    import random
    N = random.randrange(100,999)
    print("Число: ", N)
    d2 = int(N/100)
    print("Сотни: ", d2)
    
### Задание 3(9) ' Boolean 9 Даны два целых числа: A, B. Проверить истинность высказывания: « Хотя бы одно из чисел A и B нечетное » '
    
    import random
    A = random.randrange(1,10)
    B = random.randrange(1,10)
    print(" A = ", A)
    print(" B = ", B)
    a1 = (A % 2) ==1
    b1 = (B % 2) ==1
    n = a1 or b1
    print("A нечетно: ", a1)
    print("B нечетно: ", b1)
    print("Хотя бы одно из чисел A и B нечетное: ", n)
     
