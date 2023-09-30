## Pseudoklasy

Pseudoklasy są używane do definiowania specjalnych stanów elementów.

### Przykłady:

- **`:hover`**: Stosuje style, gdy kursor myszy znajduje się nad elementem.
- **`:active`**: Stosuje style, gdy element jest aktywowany (np. podczas kliknięcia myszą).
- **`:focus`**: Stosuje style, gdy element ma fokus (np. pole formularza).
- **`:nth-child()`**: Wybiera elementy na podstawie ich pozycji wśród rodzeństwa.

`button:hover { background-color: blue; } 
`li:nth-child(odd) { background-color: lightgray; }`

## Pseudoelementy

Pseudoelementy służą do stylizacji konkretnych części elementu, które nie są bezpośrednio dostępne jako elementy [[DOM (Document Object Model)]].

### Przykłady:

- **`::before`**: Dodaje zawartość przed treścią elementu.
- **`::after`**: Dodaje zawartość po treści elementu.
- **`::first-line`**: Stylizuje pierwszą linię tekstu wewnątrz elementu.

`div::before { content: "Początek"; } 
`div::after { content: "Koniec"; } 
`p::first-line { font-weight: bold; }`

## Atrybuty

Selektory atrybutów w CSS służą do wyboru elementów na podstawie ich atrybutów i wartości atrybutów.

### Przykłady:

- **`[attribute]`**: Wybiera elementy z określonym atrybutem.
- **`[attribute=value]`**: Wybiera elementy z atrybutem o określonej wartości.
- **`[attribute^=value]`**: Wybiera elementy, których wartość atrybutu zaczyna się od określonej frazy.
- **`[attribute$=value]`**: Wybiera elementy, których wartość atrybutu kończy się na określonej frazie.

`input[type="text"] { border: 1px solid gray; } 
`a[href^="https://"] { color: green; } 
`a[href$=".pdf"] { background-color: red; }`