Multiclass Kits
~~~~~~~~~~~~~~~

Version:    1.1
Author:     Argent77

Download:   https://github.com/Argent77/A7-MultiKits/releases/latest
Discussion: https://www.gibberlings3.net/forums/topic/40601-mod-multiclass-kits
            https://forums.beamdog.com/discussion/89800/mod-multiclass-kits


Ogólny zarys
~~~~~~~~~~~~

Przy użyciu tej modyfikacji możliwe jest zainstalowanie kombinacji podklas dla dostępnych w grze wieloklasowości. Pozwala to uzyskać niespotykane połączenia podklas, jak np. Kensai/Zabójca czy Berserker/Dziki Mag/Zawadiaka. Modyfikacja uwzględnia również podklasy dodane przez inne mody, jeśli zostały zainstalowane wcześniej.

Modyfikacja ta działa ze wszystkimi grami z serii Enhanced Edition w wersji 2.0 lub wyższej, z wyjątkiem PsT:EE.


Instalacja
~~~~~~~~~~

Jest to modyfikacja WeiDU, co oznacza, iż jest bardzo prosta w instalacji. Wystarczy rozpakować pobrane archiwum do katalogu z grą i uruchomić plik "setup-A7-MultiKits.exe" (Windows) albo "setup-A7-MultiKits.command" (macOS). Następnie należy postępować zgodnie instrukcjami, by dokonać instalacji.

Aby odinstalować modyfikację, wystarczy uruchomić ponownie plik "setup-A7-MultiKits.exe" (Windows) albo "setup-A7-MultiKits.command" (macOS) i postępować zgodnie z pojawiającymi się komunikatami.

Uwagi dla grających w dodatek Siege of Dragonspear (SoD):
Dodatek „Siege of Dragonspear” nie jest instalowany jak standardowa modyfikacja na platformach GoG lub Steam, w związku z czym nie może być modowany bez wcześniejszego przygotowania. Przed instalacją tej, czy jakiejkolwiek innej modyfikacji opartej na WeiDU, należy zainstalować modyfikację o nazwie „DLC Merger”.
Można ją pobrać ze strony: https://github.com/Argent77/A7-DlcMerger/releases/latest


Kompatybilność i kolejność instalacji
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Liczba możliwych do zainstalowania kombinacji podklas najprawdopodobniej przekroczy limit narzucony przez silnik gry.
Z tego względu zaleca się instalowanie tej modyfikacji po wszystkich innych modach dodających podklasy, z wyjątkiem 'Talents of Faerûn'.
Ponieważ połączenia podklas nie są wliczane do limitu ustalonego przez silnik gry, modyfikacja nie powoduje żadnych problemów w tym zakresie.

Pod względem koncepcyjnym mod pokrywa się częściowo z komponentami kategorii "Multi-classed kits" w modyfikacji 'Talents of Faerûn', a także z innymi modami, które wprowadzają połączenia podklas dla wieloklasowców, jednak technicznie powinien być z nimi kompatybilny.

Uwaga:
Ze względu na pewne niemodyfikowalne zachowania silnika gry, w połączeniach podklas z udziałem maga pojawią się pewne cechy maga specjalisty (np. zwiększona liczba dostępnych komórek na czary), nawet jeśli wybrana kombinacja nie zawiera podklasy maga specjalisty.


Komponenty
~~~~~~~~~~

Modyfikacja zawiera 10 oddzielnych komponentów, po jednym dla każdej dostępnej w grze kombinacji klas:
- Wojownik/Mag
- Wojownik/Kapłan
- Wojownik/Złodziej
- Wojownik/Mag/Złodziej
- Mag/Złodziej
- Kapłan/Mag
- Kapłan/Złodziej
- Wojownik/Druid
- Wojownik/Mag/Kapłan
- Kapłan/Łowca

Dla każdego komponentu dostępne są dwie opcje instalacji:

1. Wszystkie możliwe kombinacje

Opcja ta instaluje wszystkie możliwe kombinacje podklas w oparciu o podklasy dostępne w instalacji gry. Pewne połączenia mogą zostać pominięte ze względu na wykluczające się wzajemnie wymogi dotyczące rasy czy charakteru.
Przykładowo, połączenie podklas "Krasnoludzki Obrońca / Dziki Mag" może być niedostępne, ponieważ podklasa Dziki Mag nie jest dozwolona dla krasnoludów.

OSTRZEŻENIE:
Liczba możliwych kombinacji, jak również czas istalacji gwałtownie rosną wraz ze zwiększeniem liczby zainstalowanych wcześniej podklas.

2. Wybiorę samodzielnie

Po wybraniu tej opcji zostaje wyświetlone interaktywne menu, które pozwala zainstalować tylko wybrane połączenia podklas. Użytkownik ma też możliwość nadania własnej nazwy wybranej przez siebie kombinacji.


Autorzy
~~~~~~~

Coding and testing: Argent77

French translation: deratiseur

Polish translation: Aristo

Simplified Chinese translation: MephistoSatanDevil


Copyright Notices
~~~~~~~~~~~~~~~~~

The mod "Multiclass Kits" is licensed under the "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License"
(https://creativecommons.org/licenses/by-nc-sa/4.0/).


Historia wersji
~~~~~~~~~~~~~~~

1.2
- Added feature to automate installation of user-defined multiclass kits via ini file
- Choices of manual multiclass kit installations are saved in a custom ini file for use by the automated installation
- Added Simplified Chinese translation (thanks MephistoSatanDevil)
- Dodano tłumaczenie na język polski (podziękowania dla: Aristo)

1.1
- Dodano tłumaczenie na język francuski (podziękowania dla: deratiseur)
- Dodano do readme informację o kolejności instalacji
- Poprawiono błędy z naliczaniem dostępnych punktów biegłości
- Zniesiono limit 24 zdolności wysokiego poziomu (zbędne dla gier w wersji EE, począwszy od patcha 2.0)

1.0
- Pierwsze wydanie
