## 1. Czym jest BEM?

BEM to metodyka nazewnictwa i organizacji klas CSS, która ma na celu uczynienie arkuszy stylów bardziej czytelnymi i modułowymi. 
BEM to akronim od słów "Block", "Element" i "Modifier".

- **Block**: Niezależny komponent, który może istnieć samodzielnie.
- **Element**: Część bloku, która nie ma sensu poza nim.
- **Modifier**: Wariant bloku lub elementu.

`.block {} 
``.block__element {} 
``.block__element--modifier {}

## 2. SCSS i BEM

 Zagnieżdżanie klas w SCSS doskonale współpracuje z  BEMem, BEM bez SCSSa troche traci na sensie.

## 3. Korzyści z połączenia BEM i SCSS

-  Większa przejrzystość kodu
- Skalowalność
- Utrzymanie