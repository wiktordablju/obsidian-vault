**Wektor położenia** (wektor wodzący)
$$\vec{r} = x\vec{i} + y\vec{j} + z\vec{k}$$

**Przemieszczenie** - różnica wektorów położenia w chwili t2 oraz t1
$$\Delta \vec{r} = \vec{r}_2 - \vec{r}_1$$

**Prędkość** - pochodna wektora położenia względem czasu
$$\vec{v} = \frac{d\vec{r}}{dt}$$
czyli równoznacznie
$$\vec{v} = \frac{dx}{dt} \vec{i} + \frac{dy}{dt} \vec{j} + \frac{dz}{dt} \vec{k} = v_x \vec{i} + v_y \vec{j} + v_z \vec{k}$$

Jeśli wartość prędkości $$v = \sqrt{v_x^2 + v_y^2 + v_z^2}$$ jest stała to jest to ruch jednostajny prostolinowy, jeśli dodatkowo kierunek i zwrot prędkości się nie zmieniają.

**Przyspieszenie** - szybkość zmian wektora prędkości
$$\vec{a} = \frac{d\vec{v}}{dt}$$
czyli równoznacznie
$$\vec{a} = \frac{dv_x}{dt}\vec{i} + \frac{dv_y}{dt}\vec{j} + \frac{dv_z}{dt}\vec{k} = \frac{d^2x}{dt^2}\vec{i} + \frac{d^2y}{dt^2}\vec{j} + \frac{d^2z}{dt^2}\vec{k} = a_x\vec{i} + a_y\vec{j} + a_z\vec{k}$$

Poszczególne składowe ruchu nie wpływają na siebie wzajemnie, mogą być przez to opisywane niezależnie od siebie

**Ruchy krzywoliniowe**
$\vec{r}$ - wektor styczny
Prędkość: $$\vec{v} = v\vec{r}$$
W takim przypadku przyspieszenie to:
$$\vec{a} = \frac{d\vec{v}}{dt} = \frac{d}{dt}(v\vec{r}) = v\frac{d\vec{r}}{dt} + \vec{r}\frac{dv}{dt} = \vec{a_n} + \vec{a_r}$$
z tego przyspieszenie normalne (dośrodkowe) wynosi, gdzie $\vec{n}$ to wektor normalnej a $R$ to promień krzywizny toru, przyspieszenie to odpowiada za zmianę kierunku prędkości, przyspieszenie normalne zawsze jest skierowne do środka krzywizny toru : $$\vec{a_n} = v\frac{d\vec{r}}{dt} = \frac{v^2}{R}\vec{n}$$
gdzie pochodna $\vec{r}$ po czasie wynosi: $$|\vec{r}|\frac{d\varphi}{dt}\vec{n} = \frac{d\varphi}{dt}\vec{n} = \frac{1}{R}\frac{ds}{dt}\vec{n} = \frac{v}{R}\vec{n}$$
a przyspieszenie styczne(tangencjalne), odpowiada ono za zmianę wartości prędkości: $$\vec{a_r} = \vec{r}\frac{dv}{dt}$$
Podsumowując przyspieszenie w ruchu krzywoliniowym można wyrazić jako: $$\vec{a} = \frac{dv}{dt}\vec{r} + \frac{v^2}{R}\vec{n}$$ a samą wartość: $$a = \sqrt{a_n^2 + a_r^2}$$