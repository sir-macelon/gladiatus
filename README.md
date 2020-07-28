Gladiatus BOT by Maciejo

Zanim uruchomisz bota zapoznaj się z założeniami dotyczącymi jego działania:
1. Pierwsza przegroda w ekwipunku zarezerwowana jest na zwoje i amulety trzymane na sprzedaż, dlatego najlepiej, żeby nie było tam nic innego.
2. W drugiej przegrodzie wystarczy, żeby zawsze było wolne miejsce na item do uszlachetnienia, jeśli korzystamy z tej opcji. Wówczas należy również zadbać o to, by pierwszy slot w warsztacie był zawsze pusty.
3. W trzeciej przegrodzie powinno znajdować się tylko jedzenie. Bot sam będzie przenosić tam jedzenie z paczek, a jeśli jedzenie w paczkach się skończy, to będzie licytować je na aukcji.
4. Przegroda "Sprzedaj" u handlarza bronią powinna być zawsze pusta, bo jest używana do sprzedawania i odkupywania zwojów i amuletów z pierwszej przegrody w ekwipunku.
5. Zapoznaj się z parametrami w pliku "gladiatus.properties" i ustaw je wedle własnej potrzeby.

Jak uruchomić bota:
1. Zaloguj się do swojego konta Gladiatus w przeglądarce.
2. Znajdź wartości dwóch ciasteczek "Gladiatus_pl_40" i "PHPSESSID". Dostęp do nich różni się w zależności od przeglądarki (np. w Firefoxie jest to Shift+F9). Skopiuj te wartości do pliku "start.bat" w odpowiednich miejscach po znakach równości, bez dodawania żadnych spacji. W przypadku ciasteczka "Gladiatus_pl_40", będzie ono zawierało znak "%" (procent). Trzeba przed nim dopisać jeszcze jeden taki sam znak, żeby były dwa obok siebie: "%%".
3. Z linka otwartej strony w Gladiatusie skopiuj wartość ostatniego parametru "sh" (po znaku równości) i wklej go do tego samego pliku "start.bat" (też po znaku równości, bez dodawania spacji).
4. Po ustawieniu wszystkich trzech parametrów, uruchom bota plikiem "start.bat", a on podepnie się do przekazanej sesji logowania. Bot będzie działał w ten sposób, dopóki podana sesja logowania jest aktywna, tzn. dopóki sam się nie wylogujesz, albo zalogujesz się z innego urządzenia. Wówczas cały proces uruchomienia trzeba powtórzyć. Dlatego najlepiej nie zamykać przeglądarki i nie logować się z innych urządzeń, jak np. z telefonu.

Uwagi na temat użytkowania:
1. Gdy bot działa, będzie informował o swoim stanie aktywny/uśpiony ("waking up"/"Sleeping for"). Z racji tego, że używamy surowców jako dobówek, aby uniknąć przypadkowego ich zdeponowania do magazynu, trzeba zwrócić uwagę, czy bot jest aktualnie uśpiony i tylko wtedy deponować wszystkie surowce.