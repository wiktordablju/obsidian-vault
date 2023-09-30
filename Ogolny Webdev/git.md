## Pojęcia kluczowe 
**Repozytorium** - Miejsce, w którym przechowywane są dane o projekcie, wraz z historią zmian. **Commit** - Zapis wybranych zmian w projekcie. 
Branch  - Niezależna linia rozwoju, używana do pracy nad różnymi funkcjami lub eksperymentami bez wpływania na główną gałąź projektu.

# Podstawowe Polecenia Git

- **Inicjowanie repozytorium:**  
  `git init`

- **Klonowanie repozytorium:**  
  `git clone [URL_REPOZYTORIUM]`

- **Dodawanie plików do śledzenia:**  
  `git add [NAZWA_PLIKU]`  
  *Aby dodać wszystkie pliki:*  
  `git add .`

- **Zapisywanie zmian (commit):**  
  `git commit -m "[OPIS_ZMIAN]"`

- **Sprawdzanie statusu zmian:**  
  `git status`

- **Wyświetlenie historii commitów:**  
  `git log`

- **Wysyłanie zmian na serwer:**  
  `git push [NAZWA_GAŁĘZI]`

- **Pobieranie zmian z serwera:**  
  `git pull [NAZWA_GAŁĘZI]`

- **Tworzenie nowej gałęzi:**  
  `git branch [NAZWA_GAŁĘZI]`

- **Przełączanie między gałęziami:**  
  `git checkout [NAZWA_GAŁĘZI]`

- **Scalanie zmian z innej gałęzi:**  
  `git merge [NAZWA_GAŁĘZI]`

- **Usunięcie gałęzi:**  
  `git branch -d [NAZWA_GAŁĘZI]`

- **Wyświetlenie wszystkich gałęzi:**  
  `git branch`

- **Cofnięcie zmian:**  
  `git revert [HASH_COMMITU]`


