Niech $X \neq \emptyset$. 
Metryką na zbiorze $X$ nazywamy każdą funkcję $d: X \times X \to \mathbb{R}$ spełniającą następujące warunki: 
1. $d(x,y) = 0$ wtedy i tylko wtedy, gdy $x=y$ 
2. $d(x,y) = d(y,x)$ (symetria) 
3. $d(x,y) + d(y,z) \geq d(x,z)$ (nierówność trójkąta) 

Elementy zbioru \( X \) nazywamy **punktami**, a $d(x,y)$ to **odległość** punktu $x$ od $y$. 

**Przestrzeń metryczna** to uporządkowana para $(X,d)$, w której $d$ jest metryką na niepustym zbiorze $X$.
### Metryka dyskretna 
$d(x,y) = \begin{cases} 0, & \text{dla } x=y \\ 1, & \text{dla } x\neq y \end{cases}$ 
### Metryki euklidesowe 
- $X = \mathbb{R}, \quad d(x_1,x_2) = |x_1-x_2|$
- $X = \mathbb{C}, \quad d(z_1,z_2) = |z_1-z_2|$
- $X = \mathbb{R}^2, \quad d((x_1,y_1), (x_2,y_2)) = \sqrt{(x_1 - x_2)^2 + (y_1 - y_2)^2}$
### Metryki nieeuklidesowe w $\mathbb{R}^2$
- **Metryka taksówkowa (NY)** $d(P(x_1,y_1), Q(x_2,y_2)) = |x_1-x_2| + |y_1-y_2|$ 
	(Nazwa pochodzi od ruchu taksówek w Nowym Jorku, gdzie ulice tworzą prostokątną siatkę.) 
- **Metryka rzeki** $d(P(x_1,y_1), Q(x_2,y_2)) = \begin{cases} |y_1 - y_2|, & \text{gdy } x_1 = x_2 \\ |x_1 - x_2| + |y_1| + |y_2|, & \text{gdy } x_1 \neq x_2 \end{cases}$
### Kule i otoczenia 
Kulą o środku $P$ i promieniu $\epsilon > 0$ nazywamy zbiór: 
$\mathfrak{B}(P, \epsilon) = \{ Q \in X : d(P,Q) < \epsilon \}$

Zbiór $S$ nazywamy **ograniczonym**, gdy istnieje kula, która go zawiera.

**Otoczeniem** punktu $P$ nazywamy każdą kulę o środku $P$: $N_P = \operatorname{nbd}(P) = \mathfrak{B}(P, \epsilon)$ 
**Sąsiedztwem** punktu $P$ nazywamy każdą kulę bez środka: $D_P = \mathfrak{B}(P, \epsilon) \setminus \{P\}$
### Punkty i własności zbiorów 
- **Punkt skupienia** zbioru $S$: $P$ jest punktem skupienia, jeśli w każdym sąsiedztwie $P$ znajduje się przynajmniej jeden punkt $Q \in S$. 
- **Zbiór domknięty**: $S$ jest domknięty, jeśli wszystkie jego punkty skupienia należą do $S$. 
- **Punkt wewnętrzny** zbioru $S$: $P$ jest punktem wewnętrznym, jeśli istnieje jego otoczenie całkowicie zawarte w $S$. 
- **Zbiór otwarty**: $S$ jest otwarty, jeśli wszystkie jego punkty są punktami wewnętrznymi. 
- **Punkt izolowany**: $P$ jest punktem izolowanym, jeśli istnieje jego otoczenie, które zawiera dokładnie jeden punkt zbioru $S$. 
- **Punkt brzegowy**: $P$ jest punktem brzegowym, jeśli w każdym jego otoczeniu znajduje się przynajmniej jeden punkt należący do $S$ oraz przynajmniej jeden punkt nienależący do $S$.
### Średnica zbioru 
Średnicą niepustego i ograniczonego zbioru $S$ nazywamy liczbę: 
$\operatorname{diam}(S) = \delta(S) = \sup \{ d(P,Q) : P, Q \in S \}$
### Oznaczenia 
- **Dopełnienie zbioru**: $S' = X \setminus S$
- **Domknięcie zbioru**: $\operatorname{cl}(S) = \{ P : P \in S \text{ lub } P \text{ jest punktem skupienia } S \}$
- **Wnętrze zbioru**: $\operatorname{Int}(S) = \{ P : \exists \epsilon > 0 \text{ takie, że } \mathfrak{B}(P, \epsilon) \subseteq S \}$
- **Brzeg zbioru**: $\operatorname{Fr}(S) = \{ P : \forall \epsilon > 0, \exists Q_1 \in S \text{ oraz } Q_2 \in S' \text{ takie, że } Q_1, Q_2 \in \mathfrak{B}(P, \epsilon) \}$
