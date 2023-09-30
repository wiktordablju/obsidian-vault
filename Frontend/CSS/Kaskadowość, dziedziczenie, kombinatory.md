
## Kaskadowość

Kaskadowość to określenie w jaki sposób CSS radzi sobie z konfliktami w stylach (np. jeśli jeden element ma na sobie różne style nadane w innych miejscach). Kaskadowość opiera się na kilku czynnikach:

1. **Pochodzenie stylu**: Domyślnie CSS ma ustalone różne wartości, wszystko co nada deweloper jest nadpisywane.
2. **Ważność**: Reguły oznaczone `!important` mają pierwszeństwo przed innymi, raczej nie używać tego tylkorozwiązywać w inne spsooby.
3. **Specyficzność**: Określa, która reguła ma pierwszeństwo, opierając się na typie i liczbie selektorów.
4. **Kolejność**: W przypadku równych specyficzności, ostatnia reguła w arkuszu stylów ma pierwszeństwo.

## Dziedziczenie

Niektóre właściwości CSS są dziedziczone przez elementy potomne od ich rodziców, co oznacza, że potomek przyjmuje wartość właściwości zastosowanej do rodzica. Przykłady takich właściwości to `color`, `font-family` i `text-align`.

## Kombinatory

Kombinatory w CSS pozwalają tworzyć bardziej skomplikowane selektory, które określają relacje między elementami.

1. **Potomek ( )**: Selektor A B wybiera wszystkie elementy B, które są potomkami A.
    
    `div p { color: blue; }`
    
2. **Bezpośredni potomek (>)**: Selektor A > B wybiera wszystkie elementy B, które są bezpośrednimi dziećmi A.
    `div > p { color: red; }`
    
3. **Następny rodzeństwo (+)**: Selektor A + B wybiera element B, który bezpośrednio następuje po A.    
    `h2 + p { font-weight: bold; }`
    
4. **Wszystkie następne rodzeństwo (~)**: Selektor A ~ B wybiera wszystkie elementy B, które następują po A w tym samym kontenerze.
    
    `h2 ~ p { margin-left: 20px; }`