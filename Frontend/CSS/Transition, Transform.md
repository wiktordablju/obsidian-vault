## `transition`

transition` pozwala na płynne przejście między dwoma wartościami właściwości przez określony czas.

### Składniki:

1. **`transition-property`**: Właściwość (lub właściwości), której zmiany mają być animowane. Ważne żeby zawsze to dawać ze względów optymalizacyjnych
    
2. **`transition-duration`**: Czas trwania animacji (np. `0.3s` lub `500ms`).
    
3. **`transition-timing-function`**: Funkcja definiująca prędkość krzywej animacji, np. `linear`, `ease-in`, `ease-out`, `ease-in-out`.
    
4. **`transition-delay`**: Czas opóźnienia przed rozpoczęciem animacji.
    
### Przykład:
`.box {     transition: width 0.3s ease-in-out 0s; }`


## `transform`

`transform` pozwala na modyfikowanie układu i kształtu elementu, np. przesuwanie, skalowanie, obracanie, skos.

### Funkcje transformacji:

1. **`translate()`**: Przesuwa element wzdłuż osi X i Y.
2. **`translateX()`** & **`translateY()`**: Przesuwa element odpowiednio wzdłuż osi X lub Y.
3. **`scale()`**: Skaluje element wzdłuż osi X i Y.
4. **`scaleX()`** & **`scaleY()`**: Skaluje element odpowiednio wzdłuż osi X lub Y.
5. **`rotate()`**: Obraca element wokół punktu osi.

