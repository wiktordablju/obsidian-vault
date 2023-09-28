**1. Definicja**

- Emmet to narzędzie, które znacząco przyspiesza proces tworzenia kodu HTML i CSS dzięki skróconej składni i dynamicznemu generowaniu kodu.

**2. Podstawy**

- **Skrócone tagi**: Wpisanie skróconej nazwy tagu i naciśnięcie `Tab` generuje pełny tag. Np. `div` zamienia się na `<div></div>`.
    
- **Klasy i ID**: Używając `.` i `#` można szybko dodać klasy i ID. Np. `div.container#main` zamienia się na `<div class="container" id="main"></div>`.
    
- **Atrybuty**: W nawiasach kwadratowych można dodać atrybuty. Np. `a[href="#"]` zamienia się na `<a href="#"></a>`.
    

**3. Zaawansowane Techniki**

- **Wielokrotne elementy**: Używając `*` można generować wiele elementów. Np. `ul>li*5` generuje listę z pięcioma elementami.
    
- **Grupowanie**: Za pomocą nawiasów `()` można grupować elementy. Np. `div>(header+main+footer)`.
    
- **Relacje rodzic-dziecko**: `>` określa relację rodzic-dziecko. Np. `div>span` generuje `<div><span></span></div>`.
    
- **Sąsiedztwo**: `+` określa elementy sąsiadujące. Np. `div+div` generuje `<div></div><div></div>`.
    

**4. Skróty CSS**

- Emmet pozwala również na szybsze pisanie CSS. Np. `m10` zamienia się na `margin: 10px;`.

**5. Personalizacja i Rozszerzenia**

- Emmet jest dostępny jako rozszerzenie dla wielu popularnych edytorów kodu, takich jak Visual Studio Code, Sublime Text czy Atom.
- Można dostosować i rozszerzyć skróty Emmet według własnych potrzeb.