**Wektor położenia** (wektor wodzący)
$$\hat{r} = x\hat{i} + y\hat{j} + z\hat{k}$$

**Przemieszczenie** - różnica wektorow polozenia w chwili t2 oraz t1
$$\Delta \hat{r} = \hat{r}_2 - \hat{r}_1$$

**Prędkość** - pochodna wektora polozenia wzgledem czasu
$$\hat{v} = \frac{d\hat{r}}{dt}$$
czyli równoznacznie
$$\hat{v} = \frac{dx}{dt} \hat{i} + \frac{dy}{dt} \hat{j} + \frac{dz}{dt} \hat{k} = v_x \hat{i} + v_y \hat{j} + v_z \hat{k}$$

Jeśli wartość prędkości $$v = \sqrt{v_x^2 + v_y^2 + v_z^2}$$ jest stała to jest to ruch jednostajny

**Przyśpieszenie** - szybkość zmian wektora prędkości
$$\hat{a} = \frac{d\hat{v}}{dt}$$
czyli równoznacznie
$$\hat{a} = \frac{dv_x}{dt}\hat{i} + \frac{dv_y}{dt}\hat{j} + \frac{dv_z}{dt}\hat{k} = \frac{d^2x}{dt^2}\hat{i} + \frac{d^2y}{dt^2}\hat{j} + \frac{d^2z}{dt^2}\hat{k} = a_x\hat{i} + a_y\hat{j} + a_z\hat{k}$$

Poszczególne składowe ruchu nie wpływają na siebie wzajemnie, mogą być przez to opisywane niezależnie od siebie

**Ruchy krzywoliniowe**
$\hat{r}$ - wektor styczny
Prędkość: $$\hat{v} = v\hat{r}$$
W takim przypadku przyśpieszenie to:
$$\hat{a} = \frac{d\hat{v}}{dt} = \frac{d}{dt}(v\hat{r}) = v\frac{d\hat{r}}{dt} + \hat{r}\frac{dv}{dt} = \hat{a_n} + \hat{a_r}$$
z tego przyśpieszenie normalne (dośrodkowe) wynosi, gdzie $\hat{n}$ to wektor normalnej a $R$ to promien krzywizny toru, przyśpieszenie to odpowiada za zmianę kierunku prędkości : $$\hat{a_n} = v\frac{d\hat{r}}{dt} = \frac{v^2}{R}\hat{n}$$
gdzie pochodna $\hat{r}$ po czasie wynosi: $$|\hat{r}|\frac{d\varphi}{dt}\hat{n} = \frac{d\varphi}{dt}\hat{n} = \frac{1}{R}\frac{ds}{dt}\hat{n} = \frac{v}{R}\hat{n}$$
a przyśpieszenie styczne(tangencjalne), odpowiada ono za zmianę wartości prędkości: $$\hat{a_r} = \hat{r}\frac{dv}{dt}$$
Podsumowując przyśpieszenie w ruchu krzywoliniowym można wyrazić jako: $$\hat{a} = \frac{dv}{dt}\hat{r} + \frac{v^2}{R}\hat{n}$$ a samą wartość: $$a = \sqrt{a_n^2 + a_r^2}$$