
### 1. Stringi  
 są sekwencjami znaków. W Pythonie ciągi tekstowe są otoczone pojedynczymi (`'`), podwójnymi (`"`) lub potrójnymi (`'''` lub `"""`) cudzysłowami.  
 ### Przykłady:  
string1 = "hello world"
longString = "tekst na kilka
linijek
"

### Operacje na ciągach tekstowych:

- **Konkatenacja**: `napis1 + napis2`
- **Powielanie**: `napis1 * 3`
- **Indeksowanie**: `napis1[0]`
- **Wycinek**: `napis2[0:6]`
- **Długość**: `len(napis1)`

## 2. Liczby

- **int**: liczby całkowite (np. `5`, `-23`)
- **float**: liczby zmiennoprzecinkowe (np. `3.14`, `-0.001`)
- **complex**: liczby zespolone (np. `3+4j`, `2-3j`)

### Operacje na liczbach:

- **Dodawanie**: `5 + 3`
- **Odejmowanie**: `9 - 4`
- **Mnożenie**: `7 * 2`
- **Dzielenie**: `8 / 2`
- **Dzielenie całkowite**: `8 // 3`
- **Modulo**: `8 % 3`
- **Potęgowanie**: `2 ** 3`

## 3. Zmienne

Zmienne służą do przechowywania wartości. W Pythonie nie musisz deklarować typu zmiennej - jest on określany dynamicznie podczas przypisania wartości.

`x = 10 y = "Tekst" z = 3.14`

### Zasady nazywania zmiennych:

- Mogą zawierać tylko litery, cyfry i podkreślenia.
- Muszą zaczynać się od litery lub podkreślenia.
- Nie mogą zaczynać się od cyfry.
- Nie mogą być tzw. "słowami kluczowymi" w Pythonie (np. `if`, `and`, `or`, `not`).