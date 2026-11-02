BUDZET DOMOWY — PELNA PACZKA Z POPRAWIONA TABELA RAT

Zawartosc:
- index.html — pelna aplikacja: Budzet domowy, Rozliczenie 800+, Moje raty i Bukmacherka
- manifest.json — konfiguracja instalacji PWA
- sw.js — pamiec podreczna z nowa wersja cache, aby przegladarka pobrala aktualizacje
- icons/icon-192.png i icons/icon-512.png — ikony aplikacji

ZMIANY:
- zakladki ukladaja sie na telefonie w dwoch kolumnach, bez wychodzenia poza ekran;
- tabela „Wszystkie raty do splaty” pokazuje: Zobowiazanie, Kwota poczatkowa, Pozostalo do splaty, Rata / mies. oraz Postep splaty;
- postep pokazuje liczbe rat w formacie spłacone/wszystkie, procent i pasek postepu;
- z tabeli usunieto kolumny Dzien i Uwagi oraz przycisk „Spłacono ratę”; pozostaly przyciski Edytuj i usuwania;
- oznaczanie raty jako splaconej nadal jest dostepne w sekcji „Najblizsze raty”;
- pozostale zakladki i dotychczasowy klucz danych localStorage pozostaja zachowane.

JAK WDROZYC:
1. W aplikacji wykonaj „Eksportuj kopie” i zachowaj plik JSON.
2. Rozpakuj ZIP.
3. Wgraj zawartosc archiwum do glownego katalogu repozytorium GitHub Pages, zachowujac folder icons. Zastap istniejace pliki.
4. Zatwierdz zmiany (Commit changes) i poczekaj na zakonczenie publikacji.
5. Otworz aplikacje i odswiez strone. Jesli stara wersja nadal sie pokazuje, zamknij ja i otworz ponownie po chwili.

UWAGA O DANYCH:
Dane aplikacji sa przechowywane lokalnie w przegladarce i urzadzeniu. Zachowano klucz localStorage „budzet-domowy-v1”, wiec dane powinny pozostac na tym samym urzadzeniu i w tej samej przegladarce. Nie czysc danych witryny. Wykonaj kopie JSON przed aktualizacja.

Procent postepu jest liczony na podstawie liczby rat: liczba wszystkich rat to zaokraglenie kwoty poczatkowej / raty miesiecznej w gore. Dla rat z innymi oplatami/ostatnia rata o innej kwocie wartosc jest orientacyjna.
