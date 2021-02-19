from random import randint

n=int(input("Сколько раз подбросить монетку? "))

for i in range(n):
    b = randint(0,1)

    if (b==0):
        print("Орёл")
    else:
        print("Решка")
