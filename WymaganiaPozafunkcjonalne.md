﻿##Wymagania Pozafunkcjonalne

##Wymagania Niefizyczne

####Język programowania
java

####Technologia
Technologia Java Enterprise Edition 1.6 w tym HTML 4.01 oraz CSS2
Serwer Aplikacyjny Glassfish 3.1.2.2

####Używane Frameworki
Interfejs web przy użyciu frameworku JSF 2.1.14
Mapowanie obiektowo relacyjne przy użyciu frameworku Hibernate 4.1.8

####Baza Danych
Dwie bazy danych
System zarządzania bazą danych Oracle 11g r2 Enterprise Edition
Złożony system autoryzacji

##Wymagania Fizyczne

####Serwer glówny
Serwer oparty o technologie klastrową
Dostęp do internetu przy pomocy kilku łącz światłowodowych jednomodowych
System Awaryjnego zasilania, przeciw pożarowy, antywłamaniowy, autoryzacja dostępu fizycznego
Fizyczny Terminal Administracyjny

####Serwer Pomocy

####Baza Danych
Dwie bazy danych położone w różnych lokalizacjach fizycznych
*Pierwsza razem z serwerem
*Druga w bezpiecznej, tajnej lokalizacji połączona szybką siecią wewnętrzną

##Wymagania Dostępowe

####Terminale wyborcze
*```Terminal``` - Terminal w oparciu o system linux
*```Terminal główny``` - Moduł autoryzacji terminali dotykowych, podłączenie do internetu
*```Dotykowe terminale``` - podłączone do terminalu głównego, ograniczenie dostępu jedynie do Przeglądarki Internetowej Firefox 16.0.2 oraz blokada dostępu do domen innych niż domena głosowania


####Komputer głosującego
*Komputer klasy PC lub podobny
*Połączenie z siecią internet
*Napęd CD-ROM lub zgodny
*Przeglądarka Internetowa: Mozilla Firefox 4.0+, Opera 7+, Google Chrome 2+, Internet Explorer 7+ lub inna zgodna z HTML 4.01 oraz CSS 2


##Wymagania Bezpieczeństwa
Połączenie z serwerem musi odbywać się przez bezpieczny protokół https z szyfrowaniem ssl
Serwer musi posiadać certyfikat najwyższego poziomu wydany przez główny ośrodek certyfikacji rozpoznawany przez główne przeglądarki
System musi być zabezpieczony przez adakami SQLi, MIM, i innymi znanymi atakami
Serwery baz danych są dostępne tylko w sieci wewnętrznej
System nie przechowuje informacji na temat głosów konkretnych osób dla zapewnienia tajności głosowania

##Wymagania Wydajnościowe
Serwer musi obsłużyć conajmniej 1% urzytkowników zalogowanych w tym samym czasie
System musi być dostępny 99,999% w okresie głosowania oraz 99,99% poza nim
Serwer pomocy musi być dostępny na poziomi 99.99%
Czas kontaktu z help desk przez serwer pomocy musi być nie dłuższy niż 2 min

