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
     
###  Задание 4(9) ' If 9 Даны две переменные вещественного типа: A, B. Перераспределить значения данных переменных так, чтобы в A оказалось меньшее из значений, а в B — большее. Вывести новые значения переменных A и B '

    import random
    A = random.randrange(-5,5)
    B = random.randrange(-5,5)
    print("Число A: ", A)
    print("Число B: ", B)
    if A > B:
    A,B = B,A
    print("Число A: ", A)
    print("Число B: ", B)
### Задание 6(9) 'Даны два целых числа А и В (А > B). Найти сумму квадратов всех целых чисел от А до В включительно.
    
    import random
    A = random.randrange(10)
    n = random.randrange(10) + 1
    B = A + n 
    print('A = ', A)
    print('B = ', B)
      S = 0
       for i in range(A, B +1, 1):
       S += i*i
       print(i,":",i*i,":",s)
    print("Sum of squares = ", S)
### Задание 7(31)
    
    import random
    N = random.randrange(1,1000)
    print("N = ",N)
    a = N
    i = 0
    flag = False
    while a >= 1:
        i += 1 
        r = a % 10 
        print(i," - ", r)
        if r % 2 == 1:
           flag = True
           break
        a = int(a/10)
    print(flag)
### Задание 7(21)
    import random
    N = random.randrange(2,1000)
    print('N = ', N)
    K = 0 
    P = 1 
    while P <= N :
        P *= 3
        K += 1 
    print("K = 0, 3^K = 1, 3^(K-1) = 2".format(K, 3**K, 3**(K-1)))
