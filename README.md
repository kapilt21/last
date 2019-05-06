# last
funkcja rekur.


def srodkowa_wartosc(x):
    if len(x)%2 ==0:
        if len(x) == 2:
            return x
        else:
            return srodkowa_wartosc(x[1:-1])
    if len(x)%2 != 0:
        if len(x)==1:
            return x
        else:
            return srodkowa_wartosc(x[1:-1])

res = srodkowa_wartosc(wynik)
print(res)
