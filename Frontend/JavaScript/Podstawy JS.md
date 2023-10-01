## 1. Zmienne

Zmienne służą do przechowywania danych, które można użyć i modyfikować w kodzie. 
typy deklaracji zmienny:
var 
let - nowa, zalecana zamiast var
const - stała, ta wartość się nie zmienia w trakcie trwania kodu

`var name = "John"; 
`let age = 25; 
`const pi = 3.141592653589793;`

## 3. Nazywanie zmiennych

Zmienne nazywa się:
1. Po angielsku
2. wartości const dużymi literami
3. Używając camelCasea

## 4. Typy danych

JavaScript obsługuje kilka podstawowych typów danych:

- **Liczby** (Number): np. `123`, `3.14`
- **Ciągi znaków** (String): np. `"Hello"`
- **Boolean**: `true` lub `false`
- **Obiekt**: `{name: "John", age: 25}`
- **Tablica**: `[1, 2, 3]`
- **Null**: specjalna wartość wskazująca na brak wartości
- **Undefined**: typ, gdy zmienna została zadeklarowana, ale nie ma przypisanej wartości

## 5. Operatory

- **Przypisywania**: `=`, `+=`, `-=`, `*=`, `/=`, etc.
- **Porównania**: `==`, `===`, `!=`, `!==`, `<`, `>`, `<=`, `>=`
- **Logiczne**: `&&` (and), `||` (or), `!` (not)

## 6. Instrukcje warunkowe

Pozwalają wykonać różne instrukcje w zależności od różnych warunków.

`if (age > 18) {     console.log("Dorosły"); } 
`else {     console.log("Niepełnoletni"); }`

## 7. Tablice

To struktury danych używane do przechowywania wielu wartości w jednej zmiennej.

`let fruits = ["apple", "banana", "cherry"];`

## 8. Pętla `for`

Umożliwia wielokrotne wykonanie fragmentu kodu.


`for (let i = 0; i < 5; i++) {     
`console.log(i); }`