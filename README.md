# Repozytorium Git - Zadania

Ten projekt przedstawia zestaw zadań wykonanych przy użyciu systemu kontroli wersji Git, opartych na dwóch repozytoriach: `repo1` i `repo2`.

## Zadania

### Zadanie 1
- Utworzenie katalogu `repo1` zawierającego dwa pliki tekstowe z różną zawartością.
- Inicjalizacja repozytorium Git.
- Dodanie plików, zatwierdzenie zmian.

### Zadanie 2
- Modyfikacja zawartości plików w `repo1`.
- Sprawdzenie stanu repozytorium.
- Wyświetlenie różnic między plikami.
- Zatwierdzenie zmian, wyświetlenie historii zmian.

### Zadanie 3
- Sklonowanie repozytorium `repo1` jako `repo2`.

### Zadanie 4
- Działanie w repo2: usuwanie pliku i zmiana nazwy innego pliku.
- Sprawdzenie stanu repozytorium, zatwierdzenie zmian.
- Wyświetlenie historii zmian z informacją o nazwach zmienianych plików.

### Zadanie 5
- Aktualizacja stanu repo1, aby odzwierciedlał zmiany dokonane w repo2.

### Zadanie 6
- Równoczesna modyfikacja pliku tekstowego w repo1 i repo2 w sprzeczny sposób.
- Zatwierdzenie zmian w obu repozytoriach.
- Aktualizacja stanu repo1 z repo2, rozwiązanie konfliktu.

### Zadanie 7
- Przywrócenie stanu kopii roboczej do stanu repozytorium sprzed zadania 6.
- Wyświetlenie zawartości modyfikowanego pliku z zadania 6.
- Powrót do normalnego stanu repozytorium.

### Zadanie 8
- Wyświetlenie zawartości pliku modyfikowanego w zadaniu 6 przed dokonaniem tych modyfikacji.

### Zadanie 9
- Wyświetlenie różnicy stanu obecnego pliku modyfikowanego w zadaniu 6 i stanu przed dokonaniem tych modyfikacji.

### Zadanie 10
- Utworzenie nowego brancha w repo1 o nazwie test i przełączenie się na niego.
- Modyfikacja pliku w ramach tego brancha i zatwierdzenie zmian.
- Wyświetlenie informacji na temat branchy.
- Powrót do domyślnej gałęzi "master" i wyświetlenie zawartości modyfikowanego pliku oraz stanu repozytorium.

### Zadanie 11
- Zaciągnięcie zmian z repo1 do repo2 do brancha o nazwie test.
- Wyświetlenie stanu repozytorium, informacji na temat branchy oraz dwóch najnowszych wpisów z historii.

## Rozwiązywanie konfliktów

W przypadku wystąpienia konfliktów podczas mergowania zmian między repozytoriami `repo1` i `repo2`, proces rozwiązywania konfliktów wymaga ręcznego interweniowania.

### Rozwiązanie konfliktu

1. Użyj polecenia `git status`, aby sprawdzić pliki z konfliktami.
2. Otwórz pliki z konfliktami i ręcznie scal zmiany z różnych źródeł.
3. Użyj `git add <plik>` oraz `git commit -m "Rozwiązanie konfliktu"`.

Autor: Lefjuu
