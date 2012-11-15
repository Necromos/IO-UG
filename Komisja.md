## Komisja
#### Główne cele
Jest to główny komponent komisji wyborczej regulujący status osób głosujących jak i sprawdzający poprawność otrzymanych danych (wstępnie) oraz wysyłający odpowiednie raporty do systemu wewnętrznego wraz z listą głosujących i oddanymi głosami

## Moduły zaimplementowane
#### Panel komisji
Uruchamia dostęp do terminali ustawiając ilość możliwych do oddania głosów a w przypadku nieścisłości blokuje ów dostęp. Zatwierdza wstępną poprawność głosowania. Łączy się z wewnętrznym systemem przesyłając mu dane w zsynchronizowanych godzinach aby odciążyć go od ciągłych zapytań.

## Komunikacja wewnątrz-komponentowa
Brak
## Komunikacja zewnątrz-komponentowa
Wysyła dane wstępnie zatwierdzone otrzymane od terminalu oraz podtwierdza poprawność danych.
