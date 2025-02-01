## Postać algebraiczna 
Liczba zespolona $( z = a + bi )$, gdzie $( a, b \in \mathbb{R} )$ oraz $( i^2 = -1 )$. 
- $( a = \text{Re}(z) )$ – część rzeczywista, 
- $( b = \text{Im}(z) )$ – część urojona, 
- $( i )$ – jednostka urojona. 

Zarówno $( \text{Re}(z) )$, jak i $( \text{Im}(z) )$ należą do zbioru liczb rzeczywistych.

Liczba zespolona $( z_1 = z_2 )$ wtedy i tylko wtedy, gdy ich części rzeczywiste oraz urojone są sobie równe.
## Płaszczyzna Gaussa 
Płaszczyzna Gaussa to układ współrzędnych, w którym oś rzeczywistą i urojona przedstawiają odpowiednio części rzeczywiste i urojone liczb zespolonych.

![[Pasted image 20250201155747.png]]

## Operacje na liczbach zespolonych 
Niech $( z = a + bi )$ oraz $( w = c + di )$. 
- Liczba sprzężona do $( z )$ to $( \overline{z} = a - bi )$, 
- Suma: $( z + w = (a + c) + (b + d)i )$, 
- Różnica: $( z - w = (a - c) + (b - d)i )$, 
- Iloczyn: $[ z \cdot w = (ac - bd) + (ad + bc)i ]$, 
- Iloraz: $[ \frac{z}{w} = \frac{ac + bd}{c^2 + d^2} + \frac{bc - ad}{c^2 + d^2}i ]$.
## Moduł liczby zespolonej 
Moduł liczby zespolonej to $|z| = \sqrt{a^2 + b^2}$. 
Moduł ilorazu $|{\frac{z}{w}}|$ jest równy $\frac{|z|}{|w|}$. 
Moduł liczby zespolonej to odległość od zera na płaszczyźnie Gaussa. Moduł różnicy $( |z_1 - z_2| )$ to odległość między punktami $( z_1 )$ i $( z_2 )$ na tej płaszczyźnie.
## Postać trygonometryczna 
Liczba zespolona $( z )$ może być zapisana w postaci trygonometrycznej: $z = r (\cos \varphi + i \sin \varphi),$ gdzie $r = |z|$ oraz $( \varphi)$ to argument liczby zespolonej, czyli kąt, który liczba zespolona tworzy z osią rzeczywistą na płaszczyźnie Gaussa. 
Argument liczby zespolonej $z$, zapisany jako $\arg(z)$, może przyjmować wiele wartości, ale jego wartość w przedziale $[0, 2\pi]$ nazywamy argumentem głównym i zapisujemy jako $\text{Arg}(z)$.

Relacje: 
- $\arg(z) = \text{Arg}(z) + 2k\pi$,
- $\arg(zw) = \arg(z) + \arg(w)$, 
- $\arg\left(\frac{z}{w}\right) = \arg(z) - \arg(w)$, 
- $\arg\left(\frac{1}{w}\right) = -\arg(w)$.

Wzór de Moivre'a : $z^2 = r^2 (\cos 2\varphi + i \sin 2\varphi)$.
## Obliczanie pierwiastków algebraicznych 
Obliczmy pierwiastki trzeciego stopnia z liczby $-8i$: 
$\omega^3 = -8i$. Zakładając, że $\omega = p (\cos \alpha + i \sin \alpha)$, 
otrzymujemy: $p^3 (\cos 3\alpha + i \sin 3\alpha) = 8 (\cos -\frac{\pi}{2} + i \sin -\frac{\pi}{2})$. 
Następnie obliczamy wartość $p$ oraz $\alpha$, a następnie obliczamy pierwiastki $\omega_0, \omega_1, \omega_2$ dla $k = 0, 1, 2$.
## Pierwiastki wielomianu 
Liczba zespolona różna od zera ma $n$ pierwiastków stopnia $n$. 
Pierwiastki stopnia $n$ z liczby zespolonej leżą na okręgu, którego promień to $\sqrt[n]{|z|}$. 
Pierwiastki liczb rzeczywistych są parami sprzężonymi.
## Liczba Eulera & Postać wykładnicza
Liczba Eulera $e$ jest definiowana jako: $e = \lim_{n \to \infty} \left( 1 + \frac{1}{n} \right)^n$. 
Podstawowa tożsamość Eulera: $e^{i\varphi} = \cos \varphi + i \sin \varphi$ 
Dla $\varphi = \pi$  mamy: $e^{i\pi} + 1 = 0$. 

Postać wykładnicza liczby zespolonej: $z = |z| e^{i\varphi}$.