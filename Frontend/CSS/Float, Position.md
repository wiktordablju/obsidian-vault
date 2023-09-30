
## `position`

`position` pozwala na kontrolowanie sposobu, w jaki element jest pozycjonowany w stosunku do jego kontenera lub innego odniesienia.

### Rodzaje wartości `position`:

1. **`static`**: Domyślne zachowanie elementu. Pozycja jest określana na podstawie normalnego flowu strony.
    
2. **`relative`**: Element jest pozycjonowany względem jego początkowej lokalizacji. Możemy używać `top`, `right`, `bottom`, `left`, aby przesunąć go z tej początkowej pozycji.
    
3. **`absolute`**: Element jest pozycjonowany względem najbliższego rodzica z pozycją inna niż `static` (lub względem dokumentu, jeśli taki rodzic nie istnieje). Możemy używać `top`, `right`, `bottom`, `left`, aby określić jego dokładne położenie, zmiana następuje tylko w warstwie wizualnej.
    
4. **`fixed`**: Element jest pozycjonowany względem okna przeglądarki i nie przewija się wraz ze stroną.
    
5. **`sticky`**: Mieszanka pomiędzy `relative` a `fixed`. Element "przykleja się" do określonej pozycji podczas przewijania.
    

## `float`

nigdy kurwa nie używać, to nie 2005,  to nowy tony hawk, tylko że rapowy