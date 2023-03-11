Задача 22:
Даны два неупорядоченных набора целых чисел (может быть, с повторениями).
Выдать без повторений в порядке возрастания все те числа, которые встречаются
в обоих наборах.
Пользователь вводит 2 числа. n - кол-во элементов первого множества. m - кол-во
элементов второго множества. Затем пользователь вводит сами элементы
множеств.

#n = int(input(" vvedite chisla 1 spiska __"))
#m = int(input(" vvedite chisla 2 spiska __"))
#a = list()
#b = list()
#for i in range(n):
#    a.append(int(input("vvedite chisla 1 spiska" + str(i+1) + ":")))
#print("----")
#for i in range(m):
#    b.append(int(input("vvedite chisla 2 spiska" + str(i+1) + ":")))

#print("spisok 1:", *a)

#print("spisok 2:", *b)
#res = []
#for i in a:
#    for j in b:
#        if i == j and i not in res:
#            res.append(a[i])    
#print("rezultat:", sorted(res))

Задача 24
В фермерском хозяйстве в Карелии выращивают чернику. Она растет на круглой
грядке, причем кусты высажены только по окружности. Таким образом, у каждого
куста есть ровно два соседних. Всего на грядке растет N кустов.

import random
N = int(imput ("kollichestvo kustikiv:")
Gryad = [random.randrange(100) for i in range(n)]
max_yagod = 0
for i in range(n):
    if max_yagod < {summ := Gryad [i -2] + Gryad[i-1] + Gryad[i]}:
    max_yagod = summ 
print(Gryad, max_yagod)
