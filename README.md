# Przykładowy projekt

Pokaz przykładowego użycia GIT

## Opis zmian

* Utworzenie pustego repozytorium z wykorzystaniem polecenia ***git init***
* Utworzenie dwóch plików tekstowych *plik1.txt* i *plik2.txt* przy pomocy polecenie ***echo***, następnie dodanie ich do indeksu przy użyciu ***git add*** oraz puszczenie commita przy użyciu ***git commit***
* Dodanie trzeciego pliku *plik3.txt* oraz usunięcie pliku *plik2.txt* z wykorzystaniem polecenia ***rm***
* Zmiana nazwy pliku *plik1.txt* na *main.py* za pomocą polecenia ***mv***
* Utworzenie folderu *logs/* z plikiem *dev.log* oraz dodanie tego folderu do *.gitignore*
* Wyświetlenie historii rewizji z wykorzystaniem ***git log*** następnie wyświetlenie historii rewizji z parametrem ***-p*** pokazującym różnice wprowadzone z każdą rewizją, a następnie z parametrem ***--stat*** pokazującym skrócone statystyki każdej z zatwierdzonych zmian
* Utworzenie nowej gałęzi *testing* za pomocą polecenia ***git branch***, następnie przejście do niej z wykorzystaniem ***git checkout***. Utworzenie nowego pliku *test1.txt* dodanie go do indexu oraz zrobienie commit'a
* Przejście z powrotem do gałęzi *main* oraz scalenie jej z gałęziął *testing* poleceniem ***git merge***
