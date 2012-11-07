## Inżynieria Oprogramowania zima 2012
#### Nazwa projektu: E-Głosowanie

#### Skład grupy:
* Maciej Stankiewicz
* Przemysław Królik
* Grzegorz Melzer

## Ogólny opis
Projekt e-głosowania rozpowszechnialny w każdym mieście oraz umożliwiający zdalną kontrolę i nadzór komisji wyborczych z głównego węzła znajdującego się w głównej siedzibie komisji wyborczej miasta. Projekt będzie także umożliwiał dostęp zdalny wyborców z domu poprzez specjalne aplikacje (w fazie ustalania).

## Słownik pojęć
* ```administrator``` - osoba fizyczna sprawująca kontrolę nad wyznaczonymi zadaniami systemu, rozszczególniany na różne obowiązki/funkcje (więcej szczegółów w poszczególnych zakresach)
* ```głosujący``` - osoba fizyczna, pełna praw obywatelskich w zakresie udziału w wyborach
* ```głos``` - zanotowanie w systemie poprawnego wyboru dokonanego przez głosującego w danej turze
* ```tura``` - głosowanie dotyczące jednego wydarzenia ustalane zewnętrzenie przez organy rządowe
* ```platforma głosowania``` - elektroniczny system obsługiwany przez protokoły web-owe i serwery umieszczone w poszczególnych miastach
* ```lokal wyborczy``` - fizyczna lokalizacja służąca jako punkt naziemny do oddawania głosów z wcześniej przygotowanych i skonfigurowanych stanowisk wyposażonych w terminale
* ```terminal``` - sprzęt fizyczny odpowiedzialny za połączenie z platformą głosowania dostępny w lokalu wyborczym
* ```przewodniczący komisji``` - osoba odpowiedzialna za korygowanie poprawności ilości osób oddających głos z bazą danych i uniemożliwianie "podwójnego oddawania głosu"
* ```wsparcie techniczne``` - platforma web-owa służąca jako główny węzeł komunikacyjny z technikami pomocy
* ```technik pomocy``` - specjalista służący jako wsparcie techniczne dla użytkowników

## Moduły
* ```Formularz``` - aplikacja web-owa składająca się z warstw powiązanych z pozostałymi modułami
* ```Komisja``` -  aplet kontroli komisji okręgowej
* ```Centrala wyborcza``` - główny węzeł miasta służący jako baza danych i nazdór wyborów w rejonie
###### Podmoduły
######## Centrala wyborcza
* ```?``` - ?