
**1. Definicja**

- **Margines (`margin`)**: Zewnętrzny odstęp wokół elementu, oddzielający go od innych elementów.
- **Padding (`padding`)**: Wewnętrzny odstęp wewnątrz elementu, oddzielający zawartość od jego granic.

**2. Skrócone Właściwości**

- `margin`: Można ustawić wszystkie marginesy jednocześnie. Na przykład:
    
    - `margin: 10px`: Ustawia marginesy na wszystkich stronach na 10px.
    - `margin: 10px 20px`: Ustawia marginesy górny i dolny na 10px, a lewy i prawy na 20px.
    - `margin: 10px 20px 30px 40px`: Ustawia marginesy odpowiednio dla góry, prawej strony, dołu i lewej strony.
- `padding`: Działa podobnie do `margin`, ale dotyczy wewnętrznych odstępów.
    

**3. Automatyczne Marginesy**

- Używając wartości `auto` dla marginesu, można centrować blokowe elementy w poziomie. Na przykład: `margin: 0 auto;`.

**4. Uwagi**

- Marginesy mogą się collapsnąć, jeśli dwa pionowe marginesy stykają się ze sobą, używany jest większy margines, a mniejszy jest ignorowany.
- Paddingi nie mają tego zachowania i zawsze dodają dodatkową przestrzeń do elementu.
- Właściwość `box-sizing` może wpłynąć na to, jak paddingi wpływają na całkowite wymiary elementu.
