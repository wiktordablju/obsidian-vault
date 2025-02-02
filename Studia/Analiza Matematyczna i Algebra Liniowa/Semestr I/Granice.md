# Granice ciągów

Jeśli dany ciąg nie ma granicy, to nazywamy go **rozbieżnym**, gdy natomiast ją ma, to jest **ciągiem zbieżnym**.  

Ciąg $a_n$ ma granicę $L$ wtedy i tylko wtedy, gdy:

$\forall \epsilon > 0 \quad \exists N \in \mathbb{N} \quad \forall n > N \quad d(a_n, L) < \epsilon$

Wówczas zapisujemy:

$\lim\limits_{n \to \infty} a_n = L$

### Granice w przestrzeniach metrycznych

Ważnym aspektem przy określaniu granicy ciągu jest **przestrzeń metryczna**, w której ten ciąg się znajduje.  
Na przykład, dla liczb zespolonych:


$\lim\limits_{n \to \infty} (a_n + i b_n) = a_0 + i b_0$


wtedy i tylko wtedy, gdy:


$\lim\limits_{n \to \infty} a_n = a_0 \quad \text{oraz} \quad \lim\limits_{n \to \infty} b_n = b_0$


Liczby zespolone można traktować jako punkty na płaszczyźnie.

### Twierdzenie o jednoznaczności granicy

Niech $(X, d)$ będzie przestrzenią metryczną i niech $a_n \in X$ dla $n = 1,2,3,\dots$.  
Jeśli ciąg $\{ a_n \}$ ma granicę, to jest ona **jednoznaczna**.  

Dowód:  
Załóżmy, że istnieją dwie różne granice, $L_1$ i $L_2$.  
Wówczas można wykazać, że $L_1 = L_2$, co jest sprzecznością.

### Ograniczoność ciągu

Ciąg $\{ a_n \}$ jest ograniczony wtedy i tylko wtedy, gdy zbiór:

$\{ a_n : n \in \mathbb{N} \}$


jest ograniczony, czyli wszystkie wyrazy leżą w pewnej kuli metrycznej.

### Podciągi i zbieżność

1. Jeśli ciąg $\{ a_n \}$ jest **zbieżny**, to każdy jego **podciąg** także jest zbieżny.
2. Jeśli ciąg $\{ a_n \}$ jest **rozbieżny**, to nie oznacza to, że wszystkie jego podciągi są rozbieżne.
3. **Zbieżność podciągu** nie oznacza zbieżności całego ciągu.
4. Jeśli **wszystkie podciągi** ciągu $\{ a_n \}$ są zbieżne do $L$, to znaczy, że cały ciąg $\{ a_n \}$ jest zbieżny do $L$.
5. Jeśli dwa podciągi tego samego ciągu mają **różne granice**, to cały ciąg nie jest zbieżny.

### Wpływ dodawania/usuwania wyrazów

- **Dodanie/usunięcie skończonej liczby wyrazów** w ciągu **nie wpływa** na jego zbieżność.  
- **Dodanie/usunięcie nieskończonej liczby wyrazów** może znacząco zmienić jego charakter.

### Własności granic

$\lim\limits_{n \to \infty} a_n = L \quad \text{wtedy i tylko wtedy, gdy} \quad \lim\limits_{n \to \infty} d(a_n, L) = 0$


### Monotoniczność ciągów

Ciąg jest **monotoniczny**, jeśli jest:
- rosnący,
- malejący,
- niemalejący,
- nierosnący.

**Każdy ciąg monotoniczny, który jest ograniczony, jest także zbieżny.**

### Ważne granice


$\lim\limits_{n \to \infty} \left(1 + \frac{1}{n} \right)^n = e$


Liczba $e$  jest **niewymierna** i **przestępna**.

#### Twierdzenie o trzech ciągach

Jeśli dla ciągów $\{ a_n \}, \{ b_n \}, \{ c_n \}$ zachodzi:

$a_n \leq b_n \leq c_n$

oraz $\{ a_n \}$ i $\{ c_n \}$ są zbieżne do $L$, to także $\{ b_n \}$ jest zbieżny do $L$.

#### Podstawowe granice

$\lim\limits_{n \to \infty} n^k = +\infty, \quad \text{dla } k > 0$
$\lim\limits_{n \to \infty} \frac{1}{n^k} = 0, \quad \text{dla } k > 0$
$\lim\limits_{n \to \infty} q^n =\begin{cases}0, & \text{gdy } |q| < 1 \\1, & \text{gdy } q = 1 \\\infty, & \text{gdy } q > 1 \\\text{nie istnieje}, & \text{gdy } q \leq -1\end{cases}$
$\lim\limits_{n \to \infty} a_n = \pm \infty \Rightarrow \lim\limits_{n \to \infty} \frac{1}{a_n} = 0$
$\lim\limits_{n \to \infty} a_n = 0 \Rightarrow \lim\limits_{n \to \infty} \frac{1}{a_n} = \pm \infty$
$\text{Jeśli } \lim\limits_{n \to \infty} a_n = 0 \text{ oraz } \{ b_n \} \text{ jest ograniczony}, \text{ to } \lim\limits_{n \to \infty} (a_n b_n) = 0$


### Symbole nieoznaczone

$\frac{0}{0}, \quad \frac{\infty}{\infty}, \quad 0 \cdot \infty, \quad \infty - \infty, \quad 1^\infty, \quad \infty^0, \quad 0^0$

$\text{Jeśli } \lim\limits_{n \to \infty} a_n = 0, \text{ to } \lim\limits_{n \to \infty} \left( 1 + a_n \right)^{\frac{1}{a_n}} = e$



# Granice funkcji

## Definicja granicy Heinego w punkcie  
Niech $f: D \to Y$, gdzie $D$ jest podzbiorem $X$, a $(X, d_X)$, $(Y, d_Y)$ są przestrzeniami metrycznymi. Punkt $a$ jest punktem skupienia zbioru $D$ .  
Mówimy, że funkcja $f$ ma w punkcie $a$  granicę $L$ , jeśli:  

$\forall (x_n) \subset D \setminus \{a\}, \quad \lim_{n \to \infty} x_n = a \Rightarrow \lim_{n \to \infty} f(x_n) = L$

## Definicja granicy Cauchy’ego w punkcie  
Założenia jak wyżej. Funkcja $f$ ma w punkcie $a$ granicę $L$, jeśli:

$\forall \epsilon > 0 \; \exists \delta > 0 \; \forall x \in D \setminus \{a\}, \quad d_X(x, a) < \delta \Rightarrow d_Y(f(x), L) < \epsilon$

## Własności granicy funkcji  
1. Jeśli funkcja $f$  ma granicę w punkcie $a$, to ta granica jest jedyna.  
2. Definicje Heinego i Cauchy’ego są równoważne.  
3. **Granice jednostronne:**  
   $\lim_{x \to a} f(x) = L \quad \Leftrightarrow \quad \lim_{x \to a^-} f(x) = \lim_{x \to a^+} f(x) = L$


## Działania na granicach funkcji  
Jeśli $f(x)$ i $g(x)$  mają granice w punkcie $a$, to:  
1. $\lim_{x \to a} |f(x)| = \left| \lim_{x \to a} f(x) \right|$
2. $\lim_{x \to a} k f(x) = k \lim_{x \to a} f(x)$
3. $\lim_{x \to a} (f(x) + g(x)) = \lim_{x \to a} f(x) + \lim_{x \to a} g(x)$
4. $\lim_{x \to a} (f(x) \cdot g(x)) = \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)$
5. $\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}$, jeśli $\lim_{x \to a} g(x) \neq 0$.  

## Twierdzenie o trzech funkcjach  
Niech $f(x), g(x), h(x)$ będą funkcjami rzeczywistymi, a $a$ punktem skupienia dziedzin tych funkcji.  
Jeśli dla pewnego otoczenia punktu $a$ zachodzi:
$f(x) \leq g(x) \leq h(x)$
oraz  
$\lim_{x \to a} f(x) = \lim_{x \to a} h(x) = L$
to:
$\lim_{x \to a} g(x) = L$

## Ważne granice  
$\lim_{x \to 0} (1 + x)^{\frac{1}{x}} = e$
$\lim_{x \to \infty} \left( 1 + \frac{1}{x} \right)^x = e$
$\lim_{x \to -\infty} \left( 1 + \frac{1}{x} \right)^x = e$
$\lim_{x \to 0} \frac{a^x - 1}{x} = \ln a$


# Ciągłość funkcji

## Definicja ciągłości Heinego i Cauchy’ego  
Niech $f: D \to Y$, gdzie $D \subseteq X$, a $(X, d_X)$, $(Y, d_Y)$ są przestrzeniami metrycznymi. Punkt $a$ należy do dziedziny $D$.  
Funkcja $f$ jest ciągła w punkcie $a$, jeśli:

**Definicja Heinego:**  
$\forall (x_n) \subset D, \quad \lim_{n \to \infty} x_n = a \Rightarrow \lim_{n \to \infty} f(x_n) = f(a)$

**Definicja Cauchy’ego:**  
$\forall \epsilon > 0 \; \exists \delta > 0 \; \forall x \in D, \quad d_X(x, a) < \delta \Rightarrow d_Y(f(x), f(a)) < \epsilon$


## Różnica między granicą a ciągłością  
- W **granicy** punkt \( a \) musi być punktem skupienia \( D \), ale nie musi należeć do dziedziny funkcji.  
- W **ciągłości** punkt \( a \) musi należeć do dziedziny funkcji, ale nie musi być punktem skupienia.  

## Klasyfikacja nieciągłości  
Funkcja \( f \) jest nieciągła w punkcie \( a \), jeśli:  
6. **Nieciągłość I rodzaju (usuwalna, skok skończony):** Istnieją obie granice jednostronne w punkcie \( a \), są skończone, ale różne.  
7. **Nieciągłość II rodzaju (skok nieskończony, oscylacyjna):** Co najmniej jedna granica jednostronna jest niewłaściwa.  

## Własności funkcji ciągłych  
Jeśli funkcje \( f \) i \( g \) są ciągłe w punkcie \( a \), to funkcje:  
- $k f(x)$  
- $f(x) + g(x)$
- $f(x) \cdot g(x)$  
- $\frac{f(x)}{g(x)}$ (jeśli $g(x) \neq 0$)

są ciągłe w \( a \).  

Jeśli \( f \) jest ciągła w \( a \), a \( g \) jest ciągła w $b = f(a)$, to $g \circ f$ jest ciągła w $a$.  

Funkcja odwrotna do funkcji ciągłej i ściśle monotonicznej jest ciągła w przedziale, w którym jest określona.  

## Twierdzenia o funkcjach ciągłych  

### Twierdzenie Darboux  
Jeśli $f: [a, b] \to \mathbb{R}$ jest ciągła, to dla każdej liczby $d$ zawartej między $f(a)$ a $f(b)$ istnieje $c \in (a, b)$ takie, że $f(c) = d$.  

### Twierdzenie o miejscu zerowym  
Jeśli $f: [a, b] \to \mathbb{R}$ jest ciągła i $f(a) \cdot f(b) < 0$, to istnieje $c \in (a, b)$ takie, że $f(c) = 0$.  

### Twierdzenie Weierstrassa  
Jeśli \( f: [a, b] \to \mathbb{R} \) jest ciągła, to osiąga swoje kresy, czyli jest ograniczona i przyjmuje wartości największą i najmniejszą.  

## Oscylacja funkcji  
Oscylacja funkcji \( f \) w przedziale $[a, b]$ to różnica między największą i najmniejszą wartością funkcji:
$\omega = M - m$

## Partycja przedziału  
Partycja przedziału $[a, b]$ to zbiór:
$P_n = \{ x_0, x_1, ..., x_n \}, \quad a = x_0 < x_1 < ... < x_n = b$

Jeżeli \( f \) jest ciągła na $[a, b]$, to istnieje taka partycja, że oscylacja na każdym podprzedziale jest mniejsza niż dowolnie ustalona liczba dodatnia:
$\omega_i = M_i - m_i < \epsilon$
