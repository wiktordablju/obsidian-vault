**1. Definicja**

- Właściwość `box-sizing` określa, jak przeglądarka powinna obliczać całkowite wymiary elementu w odniesieniu do paddingów, ramek i zawartości.

**2. Kluczowe Wartości**

- `content-box`: Domyślna wartość. Wymiary `width` i `height` odnoszą się tylko do zawartości elementu, nie uwzględniając paddingów ani ramek. Całkowity rozmiar elementu to `width`/`height` + `padding` + `border`.
    
- `border-box`: Wymiary `width` i `height` uwzględniają zawartość, paddingi oraz ramki. Całkowity rozmiar elementu to dokładnie wartość `width` lub `height`.

Domyślnie używa się tylko border-boxa, content-box tylko wszystko komplikuje

