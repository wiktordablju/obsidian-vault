
[Tablice pochodnych i całek](https://platforma.polsl.pl/rms/pluginfile.php/195961/mod_resource/content/1/der_int.pdf)

---

## 1. Zbadać monotoniczność i znaleźć ekstrema funkcji

1. **Wyznaczyć dziedzinę**
2. **Obliczyć pochodną**
3. **Wyznaczyć dziedzinę pochodnej** (musi zawierać się w dziedzinie oryginalnej funkcji)
4. **Rozwiązać nierówność dla pochodnej** (najczęściej $( f'(x) > 0 )$ lub $( f'(x) < 0 )$)
5. **Tabelka**:
   - $( f'(x) < 0 )$: funkcja maleje
   - $( f'(x) > 0 )$: funkcja rośnie
   - Punkt, w którym $( f'(x) = 0 )$: lokalne minimum/maksimum
6. **Odpowiedź**

---
## 2. Równanie stycznej i normalnej

### Równanie stycznej:
$f'(a)(x-a) = y - f(a)$

### Równanie normalnej:
$y - f(a) = \frac{-1}{f'(a)}(x-a)$

**Przypadki:**

- **Podana funkcja i odcięta**: Wyznaczasz pochodną, wartość funkcji i pochodnej w punkcie, a następnie podstawiasz pod równania.
- **Podana funkcja i punkt**: Jeśli dany punkt to np. $( (x, y) = (2, 3) )$, to liczysz $( f(2) = 3 )$, pochodną, i podstawiasz do równań.

### Styczna i normalna do podanej krzywej w punkcie odpowiadającym $( t_0 )$:
1. Wyznaczasz współczynnik kierunkowy stycznej:
	$a = f'(x_0) = \frac{y'(t_0)}{x'(t_0)}$
2. Wyznaczasz współczynnik normalnej:
	$a_n = -\frac{1}{a} = -\frac{1}{f'(x_0)}$
3. Równanie stycznej:
	$y = a \cdot x + b$
4. Liczysz pochodne \( x \) i \( y \), następnie podstawiasz $( t_0 )$, aby znaleźć $( x_0 )$ i $( y_0)$.

### Równanie prostej przechodzącej przez punkt \( A \) i stycznej do krzywej:
1. Liczysz pochodną $( f'(x) )$.
2. Wyznaczasz wartość pochodnej i funkcji w $( x_0)$ (mimo że na początku $( x_0)$ nie jest znane).
3. Układasz równanie stycznej i wyznaczasz $( x_0)$.
4. Podstawiasz $( x_0)$ do \( f'(x) \) i \( f(x) \), aby uzyskać równanie stycznej.

### Znaleźć punkt styczności, jeśli styczna do krzywej \( C \) jest:

- **Prostopadła do prostej \( l \)**:
	$f'(x_0) \cdot m = -1$
- **Równoległa do prostej \( l \)**:
	$f'(x_0) = m$

1. Liczysz \( a \), $( f'(x_0) )$, pochodne \( y \) i \( x \).
2. Wyznaczasz $( f'(x_0) )$ z wzoru $( \frac{y'}{x'})$.
3. Podstawiasz $( t_0 )$  do  $( x_0 )$ i  $( y_0 )$, aby znaleźć punkt styczności.

---

## 3. Wartość przybliżona z różniczki

1. Wyznaczasz funkcję \( f(x) \).
2. Wyznaczasz punkt $( x_0 )$.
3. Wyznaczasz $( \Delta t )$ w zależności od $( x_0 )$.
   - Przykład: Jeśli masz $( \frac{9.003}{10.003} )$, to funkcja to $( f(x) = \frac{x}{x+1} )$, $( x_0 = 9 )$, a $( \Delta t = 0.003 )$.
4. Liczysz $( f(x_0) )$
5. Wyznaczasz pochodną $( f'(x) )$ i wartość $( f'(x_0) )$.
6. Liczysz przybliżenie różniczkowe:
	$df(x_0) = f'(x_0) \cdot \Delta t$
7. Ostateczne przybliżenie
	$\text{Przybliżenie} \approx f(x_0) - df(x_0)$

