szukanie wartosci w sorted tablicy - lepiej strzelac w srodek(rekurencja) func(tab, zakres poczatkowy, z koncowy, dlugosc tablicy)

na ile sposobow zapisac liczbe rekurencyjnie np 5 za pomoca max trojek
hmc(z,n)
jesli n lub z to 1:
	return 1
	else
		jesli z wieksze lub rowne n
			return 1 + hmc(z, z-1)
		else
			return hmc z-n, n + hmc z, n-1

algorytm kon w szachach odwiedza kazde pole tylko raz
rekurencyjnie labirynt (niby zadanie egzaminacyjne niekiedy)
n queen problem szachowy