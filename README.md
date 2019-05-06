# last
funkcja rekur.

#User must to type some numbers. Next these numbers will be add to list.

def pobierz_dane(liczba_cyfr):
    lista = []
    for i in range(liczba_cyfr):
        lista.append(int(input("Podaj liczbę: ")))
    return lista

liczba_cyfr = int(input("Ile chcesz liczb: "))
wynik = pobierz_dane(liczba_cyfr)
print(wynik)
