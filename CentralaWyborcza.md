## Centrala wyborcza
#### Główne cele
Serce projektu, główny system podzielony na warstwy abstrakcji (prezentacji, biznesowa, danych) korelujących z sobą i odpowiedzialnych za czynności związane głównie z spójnością oraz poprawnością danych jak i zewnętrzną kontrolą i ustawianiem systemu.
## Moduły zaimplementowane
#### Front-end
"Produkt końcowy" widoczny dla głosującego z poziomu przeglądarki internetowej lub poprzez terminal dostępny w komisji wyborczej.
#### Panel administracyjny
Główny panel odpowiedzialny za sprawdzanie poprawności działania systemu i dostęp do logów serwerowych.
#### Panel statystyczny
Dostępny dla analityków/pracowników spradzających poprawność danych oraz przebieg głosowania.
#### Panel twórcy
Panel uruchamiany bezpośrednio przed rozpoczęciem głosowania dostępny tylko najwyżej uprzywilejowanym osobą z "zewnątrz". Służy do układania formularzy wyświetlanych przez Front-end oraz tworzenie zaplecza dla sesji głosowania.
## Komunikacja wewnątrz-komponentowa
Stricte według modelu aplikacji biznesowych. Każdy element modułów jest powiązany z resztą systemu i bardzo zależny od nich.
## Komunikacja zewnątrz-komponentowa
Kontrola jak i otrzymywanie informacji od komponentu Komisja w celach regulacyjnych oraz uzupełnieniowych bazy danych.
