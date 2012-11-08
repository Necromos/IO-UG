## Inżynieria Oprogramowania zima 2012
#### Nazwa projektu: E-Głosowanie

#### Skład grupy:
* Maciej Stankiewicz
* Przemysław Królik
* Grzegorz Melzer

## Ogólny opis
Projekt e-głosowania rozpowszechnialny w każdym mieście oraz umożliwiający zdalną kontrolę i nadzór komisji wyborczych z głównego węzła znajdującego się w głównej siedzibie komisji wyborczej miasta. Projekt będzie także umożliwiał dostęp zdalny wyborców z domu poprzez specjalne aplikacje (w fazie ustalania).

## Słownik pojęć
([Dostępny tutaj](http://github.com/Necromos/IO-UG/blob/master/SłownikPojęć.md))


## Komponenty
* ```Komisja``` -  aplet kontroli komisji okręgowej wraz z obsługą zarządzania terminali
* ```Centrala wyborcza``` - główny komponent służący do kontroli działania pozostałych krytycznych części systemu
* ```Pomoc techniczna``` - główny komponent pomocy technicznej składający się z wysczególnionyc

#### Modułu
* ```Front-end``` - zewnętrzny dostęp głosujących do zasobów aplikacji
* ```Panel komisji``` - moduł nadzorujący integralność danych z terminali
* ```Panel administracyjny``` - nadzór spójności systemu oraz wgląd w niekrytyczne części
* ```Panel statystyczny``` - dostęp do niekrytycznych danych potrzebnych przy wyciąganiu wyników oraz kontroli przebiegu głosowania
* ```Panel twórcy``` - terminal dostępowy bezpośrednio z lokalizacji serwera na specjalnych prawach osobom odpowiedzialnym za tworzenie ankiet głosowania i sprawdzania ich poprawności
* ```Automatyczny system pomocy``` - moduł odpowiedzialny za zdalne (bez użycia osoby żywej) odpowiadanie na pytania głosujacych
* ```Bezpośredni systme pomocy``` - moduł kontaktu bezpośredniego pomiędzy głosującym a technikiem pomocy