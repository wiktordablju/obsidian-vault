## 1. Czym jest SASS? SASS czy SCSS?

Syntactically Awesome Stylesheets - preprocesor CSS, który pozwala na korzystanie z funkcji, które nie są dostępne w standardowym CSS, takich jak zmienne, zagnieżdżenia, mixiny, dziedziczenie.
Wersje SASSa:
- **SASS** (starsza wersja z wcięciami, bez nawiasów klamrowych i średników)
- **SCSS** (nowsza wersja, bardziej zbliżona do CSS, z nawiasami klamrowymi i średnikami).

Używa się tylko SCSS obecnie

## 2. Kompilacja

Przeglądarka odczytuje tylko pliki CSS, więc trzeba przekompilować SASS na CSS, zwykła wtyczka do VSC ewentualnie terminalowo.

## 3. Sourcemap

Sourcemaps to pliki, które pozwalają devtoolsom  wskazać dokładne miejsce w oryginalnym pliku źródłowym, skąd pochodzi dany fragment skompilowanego CSS. Ułatwia to debugowanie.
(Zamiast pokazywać linijkę gdzię dana wartość jest w pliku .css to pokazuje ci ten w ktrórym ty pracujesz .scss)

## 4. html: root

W czystym CSS, można definiować zmienne w `:root`, które będą dostępne globalnie dla całego dokumentu, jednak robiąc to SASSem jest łatwiejsze.
## 5. Zmienne

W SASS zmienne definiuje się za pomocą `$`.

`$font-size: 16px;  
`body {     font-size: $font-size; }`

## 6. Mapy

Mapy w SASS to struktury podobne do tablic asocjacyjnych czy obiektów w innych językach programowania.

`$colors: (     primary: blue,     secondary: red );

## 7. Mixin

Mixiny w SASS to zestawy deklaracji, które można wielokrotnie używać w całym stylu.


`@mixin rounded-corners {     border-radius: 10px; }  
``.button {     @include rounded-corners; }

## 8. @import (obsolete)

Dyrektwa `@import` w SASS była używana do załączania jednego pliku SASS w innym. Jest jednak przestarzała i używa się `@use`. (optymalizacja)

## 9. @use

Dyrektwa `@use` to nowoczesniejsza alternatywa dla `@import`, która pozwala na załączanie innych plików SASS i korzystanie z ich zmiennych, funkcji, mixiny itp. w bardziej kontrolowany sposób.

`@use 'path/to/module';  
``.body {     font-size: module.$font-size; }