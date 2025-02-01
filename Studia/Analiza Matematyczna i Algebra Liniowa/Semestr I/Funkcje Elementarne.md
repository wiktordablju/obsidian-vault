## Monotoniczność funkcji 
Funkcja $f$ jest: 
- **monotoniczna**, jeśli jest rosnąca, malejąca, niemalejąca lub nierosnąca w swojej dziedzinie, 
- **ściśle monotoniczna**, jeśli jest tylko rosnąca lub tylko malejąca, 
- **kawałkami monotoniczna**, jeśli można ją podzielić na skończoną liczbę rozłącznych przedziałów, w których jest monotoniczna.
## Parzystość i nieparzystość funkcji
- Funkcja jest **parzysta**, gdy jest symetryczna względem osi $Y$, tj. $f(-x) = f(x)$. 
- Funkcja jest **nieparzysta**, gdy jest symetryczna względem punktu $(0,0)$, tj. $f(-x) = -f(x)$.
## Funkcje elementarne z deklaracji 
- $U(x) = 1$ – funkcja jednostkowa, 
- $\operatorname{id}(x) = x$ – funkcja tożsamościowa, 
- $\exp(x) = e^x$ – funkcja wykładnicza o podstawie $e$, 
- $\sin(x)$ – funkcja sinus.
## Funkcje trygonometryczne
- $f(x) = \sin(x)$
![[Pasted image 20250201164308.png]]
- $f(x) = \cos(x)$
![[Pasted image 20250201164339.png]]
- $f(x) = \tan(x)$
![[Pasted image 20250201164429.png]]
- $f(x) = \cot(x)$
![[Pasted image 20250201164454.png]]

### Wartosci funkcji trygonometrycznych
![[proste_rownania_trygonometryczne_18.png]]

### Znaki funkcji trygonometrycznych 
- **I ćwiartka** $(0, \pi/2)$ – wszystkie dodatnie, 
- **II ćwiartka** $(\pi/2, \pi)$ – tylko $\sin$ dodatni, 
- **III ćwiartka** $(\pi, 3\pi/2)$ – $\tan$ i $\cot$ dodatnie, 
- **IV ćwiartka** $(3\pi/2, 2\pi)$ – tylko $\cos$ dodatni.

### Wzory trygonometryczne 
- **Jedynka trygonometryczna**: $\sin^2 x + \cos^2 x = 1$, 
- $\sin 2x = 2\sin x\cos x$, 
- $\cos 2x = \cos^2 x - \sin^2 x$, 
- $\sin(x+y) = \sin x \cos y + \cos x \sin y$, 
- $\cos(x+y) = \cos x \cos y - \sin x \sin y$, 
- $\sin x + \sin y = 2 \sin \frac{x+y}{2} \cos \frac{x-y}{2}$, 
- $\cos x + \cos y = 2 \cos \frac{x+y}{2} \cos \frac{x-y}{2}$.

## Funkcje cyklometryczne
- **Arkus sinus**: $y = \arcsin x \iff x = \sin y$, gdzie $x \in [-1,1]$, $y \in [-\pi/2, \pi/2]$.
![[Pasted image 20250201165656.png]]
- **Arkus kosinus**: $y = \arccos x \iff x = \cos y$, gdzie $x \in [-1,1]$, $y \in [0, \pi]$.
![[Pasted image 20250201165723.png]]
- **Arkus tangens**: $y = \arctan x \iff x = \tan y$, gdzie $x \in \mathbb{R}$, $y \in (-\pi/2, \pi/2)$.
![[Pasted image 20250201165819.png]]
- **Arkus kotangens**: $y = \operatorname{arccot} x \iff x = \cot y$, gdzie $x \in \mathbb{R}$, $y \in (0, \pi)$.
![[Pasted image 20250201165848.png]]

## Funkcje wykładnicze i logarytmiczne 
Funkcja odwrotna do wykładniczej to logarytm naturalny $\ln$.
- $y = \ln x \iff x = e^y$, gdzie $x > 0$, $y \in \mathbb{R}$.
![[Pasted image 20250201165946.png]]

### Własności logarytmów 
- $\log_a b + \log_a c = \log_a (bc)$, 
- $\log_a b - \log_a c = \log_a \frac{b}{c}$, 
- $\log_a b^k = k \log_a b$, 
- $\log_a b = \frac{\log_c b}{\log_c a}$.

## Funkcje hiperboliczne
- **Sinus hiperboliczny**: $\sinh x = \frac{e^x - e^{-x}}{2}$,
![[Pasted image 20250201170202.png]]
- **Kosinus hiperboliczny**: $\cosh x = \frac{e^x + e^{-x}}{2}$,
![[Pasted image 20250201170221.png]]
- **Tangens hiperboliczny**: $\tanh x = \frac{\sinh x}{\cosh x}$,
![[Pasted image 20250201170237.png]]
- **Kotangens hiperboliczny**: $\coth x = \frac{1}{\tanh x}$.
![[Pasted image 20250201170255.png]]