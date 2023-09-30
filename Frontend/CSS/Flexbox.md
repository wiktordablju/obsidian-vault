
## Właściwości dla kontenera

- **`display`**: Określa, czy kontener jest flexboxem.  `display: flex;` lub `display: inline-flex;`.
- **`flex-direction`**: Określa kierunek głównej osi.  `row`, `row-reverse`, `column`, `column-reverse`.
- **`flex-wrap`**: Określa, czy elementy flex powinny owijać się.  `nowrap`, `wrap`, `wrap-reverse`.
- **`justify-content`**: Wyrównuje elementy wzdłuż głównej osi. `flex-start`, `flex-end`, `center`, `space-between`, `space-around`.
- **`align-items`**: Wyrównuje elementy wzdłuż osi poprzecznej. `flex-start`, `flex-end`, `center`, `baseline`, `stretch`.
- **`align-content`**: Wyrównuje linie flex w przypadku, gdy jest więcej niż jedna linia. `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `stretch`.

## Właściwości dla elementów flex

- **`order`**: Określa kolejność elementów w kontenerze. Domyślnie: `0`.
- **`flex-grow`**: Określa, jak duży udział element powinien mieć w dostępnym miejscu. Domyślnie: `0`.
- **`flex-shrink`**: Określa, jak element powinien się zmniejszać, jeśli brakuje miejsca. Domyślnie: `1`.
- **`flex-basis`**: Określa domyślny rozmiar elementu przed rozdysponowaniem dostępnego miejsca. `auto`, `20%`.
- **`flex`**: Skrócona forma dla `flex-grow`, `flex-shrink` i `flex-basis`.
- **`align-self`**: Pozwala na indywidualne wyrównanie elementu, nadpisując `align-items` kontenera. `auto`, `flex-start`, `flex-end`, `center`, `baseline`, `stretch`.