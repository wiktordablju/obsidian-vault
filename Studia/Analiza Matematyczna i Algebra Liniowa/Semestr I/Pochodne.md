# Pochodna i różniczka

Pochodną funkcji $f$ w punkcie $a$ nazywamy liczbę:
$f'(a) = \lim_{\Delta x \to 0} \frac{f(a + \Delta x) - f(a)}{\Delta x}$

Jeśli powyższa granica istnieje i jest skończona, to funkcja $f$ jest różniczkowalna w punkcie $a$.

Jeśli $f$ jest różniczkowalna w $a$, to:
- $f'(a)$ jest współczynnikiem kierunkowym stycznej do krzywej $y = f(x)$ w punkcie $(a, f(a))$.
- Równanie stycznej:  $y - f(a) = f'(a)(x - a)$

Funkcja różniczkowalna w punkcie jest również ciągła w tym punkcie, ale ciągłość nie jest wystarczającym warunkiem różniczkowalności.  
Funkcje różniczkowalne są "gładkie".

Jeśli dla każdego $x$ należącego do $D_{f'} \subset D_f$ istnieje liczba $f'(x)$, to możemy zdefiniować pochodną funkcji.

## Podstawowe wzory na pochodne

Jeśli $f$ i $g$ są różniczkowalne, a $c$ jest stałą rzeczywistą, to:
$(cf)' = cf'$
$(f+g)' = f' + g'$
$(fg)' = f'g + fg'$
$\left(\frac{f}{g}\right)' = \frac{f'g - fg'}{g^2}, \quad g \neq 0$
## Twierdzenie o pochodnej funkcji odwrotnej

Jeśli funkcja $y = f(x)$ jest ciągła i ściśle monotoniczna w pewnym przedziale oraz istnieje taki punkt $x_0$ należący do tego przedziału, że $f'(x_0) \neq 0$, to istnieje pochodna funkcji odwrotnej $x = f^{-1}(y)$ w punkcie $y_0 = f(x_0)$ i jest ona równa:
$\left(f^{-1}\right)'(y_0) = \frac{1}{f'(x_0)}$
## Twierdzenie o pochodnej funkcji złożonej
$(g \circ f)'(x_0) = g'(f(x_0)) \cdot f'(x_0)$

---
# Zastosowanie pochodnej

## Twierdzenie Fermata

Jeśli funkcja $f$ jest zdefiniowana w przedziale $(a, b)$, osiąga ekstremum globalne w punkcie $c$ i jest w tym punkcie różniczkowalna, to:
$f'(c) = 0$
## Twierdzenie Rolle’a

Jeśli funkcja $f$ spełnia warunki:
1. Jest ciągła w przedziale $\langle a, b \rangle$,
2. Jest różniczkowalna w przedziale $(a, b)$,
3. Spełnia warunek $f(a) = f(b)$,

to istnieje taki punkt $c$, że: $f'(c) = 0$
## Twierdzenie Lagrange’a (twierdzenie o wartości średniej)

Jeśli funkcja $f$ spełnia warunki:
1. Jest ciągła w przedziale $\langle a, b \rangle$,
2. Jest różniczkowalna w przedziale $(a, b)$,
to istnieje taki punkt $c$, że: $f'(c) = \frac{f(b) - f(a)}{b - a}$
## Twierdzenie Cauchy’ego

Jeśli funkcje $f$ i $g$ są ciągłe w przedziale $\langle a, b \rangle$ oraz różniczkowalne w $(a, b)$, a dodatkowo $g'(x) \neq 0$ dla każdego $x$ z $(a, b)$, to istnieje taki punkt $c$, że:
$\frac{f'(c)}{g'(c)} = \frac{f(b) - f(a)}{g(b) - g(a)}$
---
# Ekstrema funkcji

Funkcja $f$ ma **minimum lokalne** w punkcie $a$, jeśli istnieje $\delta > 0$, takie że dla każdego $x$ należącego do $(a - \delta, a) \cup (a, a + \delta)$:
$f(x) > f(a)$
Analogicznie, jeśli $f(x) < f(a)$, to punkt $a$ jest **maksimum lokalnym**.
Jeśli $f$ ma ekstremum w punkcie $a$, to:
$f'(a) = 0 \quad \text{lub} \quad f'(a) \text{ nie istnieje}$

Jeżeli funkcja $f$ jest ciągła w punkcie krytycznym $a$ i $f'$ zmienia znak przy przejściu przez $a$, to $f(a)$ jest ekstremum lokalnym.

---
# Wypukłość funkcji

Funkcję $f$ nazywamy **wypukłą** w przedziale $I$, jeśli dla każdego $x_1, x_2 \in I$, $x_1 \neq x_2$, oraz dla każdej  $\lambda \in (0,1)$ zachodzi:
$f(\lambda x_1 + (1 - \lambda)x_2) \leq \lambda f(x_1) + (1 - \lambda) f(x_2)$
Jeżeli $f$ jest wypukła w $I$, to funkcja $-f$ jest **wklęsła** w $I$.

---

# Asymptoty funkcji
!!!! todo
- **Asymptoty poziome**  
- **Asymptoty pionowe**  
- **Asymptoty lewo- i prawostronne**  

---

# Reguła de l’Hospitala

Jeśli funkcje $f$ i $g$ spełniają warunki:
1. Są ciągłe w przedziale $\langle a, b \rangle$,
2. Są różniczkowalne w tym przedziale,
3. $g(x) \neq 0$ oraz $g'(x) \neq 0$,
4. Granice $\lim_{x \to a^+} f(x)$ i $\lim_{x \to a^+} g(x)$ są równe $0$,
to jeśli istnieje granica:
$\lim_{x \to a^+} \frac{f'(x)}{g'(x)}$
to zachodzi: $\lim_{x \to a^+} \frac{f(x)}{g(x)} = \lim_{x \to a^+} \frac{f'(x)}{g'(x)}$


---

# Szeregi Taylora i Maclaurina
todo!!!
- **Wzór Taylora**  
- **Wzór Maclaurina**  
