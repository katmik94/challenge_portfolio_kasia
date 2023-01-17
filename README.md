# Task 1
## Subtask 1
9 punktów
## Subtask 3
Stawiam pierwsze kroki w kierunku zostania testerką i zdecydowałam się na wzięcie udziału w Challenge Portfolio, ponieważ jest to świetny sposób na zdobycie wiedzy, a także na stworzenia właśnie swojego portfolio. Podczas wykonywania zadań bedę mogła też utrwalić sobie i sprawdzić wiedzę w praktyce, co jest według mnie najlepszym sposobem na naukę 🙂. Cotygodniowe zadania są też dla mnie dodatkową motywacją do systematycznej nauki i pracy.

Moim celem jest wykorzystanie zdobytej podczas projektu wiedzy i powstałego portfolio do stania się w przyszłości zawodowym testerem oprogramowania.
## Subtask 4
<b>1. Do czego służy aplikacja?</b>

Aplikacja służy skautom do przeglądania zawodników i śledzenia ich umiejętności, do sprawdzania ich gry podczas meczów. 

<b>2. Funkcjonalności aplikacji:</b>
- logowanie do systemu oraz wylogowanie się z systemu - ta funkcja jest intuicyjna, logowanie jest proste a opcja wylogowania widoczna.
- zmiana języka na angielski - opcja dobrze widoczna.
- dodanie gracza - według mnie funkcja dodania gracza zamiast w linkach pomocniczych powinna być umieszczona nad tabelą graczy (podobnie jak jest dodaj mecz). Jego umiejscowienie byłoby wtedy bardziej intuicyjne. Proces dodania gracza jest intuicyjny.
- edycja gracza - ta opcja jest dostępna jako kliknięcie w wiersz z danym zawodnikiem, a lepiej by było, gdyby opcja edycji była umieszczona np. na końcu wiersza jako ikona (podobnie jak jest w meczach). Na ten moment nie jest możliwe przejrzenie informacji o graczu bez jednoczesnego włączenia opcji edycji, co według mnie nie jest dobrym rozwiązaniem.
- dodanie meczu - ta opcja jest dobrze widoczna i intucyjna, proces dodawania meczu także.
- edycja meczu - opcja edycji meczu jest intuicyjna, proces edycji także. Tu także informacji o meczu nie da się zobaczyć bez jednoczesnego włączenia edycji.
- dodanie przebiegu akcji - mało intuicyjna opcja, ikonki są nie podpisane, przy pierwszej próbie dodania akcji nie za bardzo wiadomo jak to zrobić. Dobrą opcją by tu było dodanie instrukcji krok po kroku jak dodać akcje do przebiegu meczu.
- generowanie raportu i edycja - generowanie raportu jest proste, edycja także. Tutaj opcja dodania raportu nad listą raportów według mnie nie koniecznie jest potrzebna, ponieważ opcja ta odsyła do listy meczów, gdzie raport jest tak na prawdę generowany, wprowadza to w błąd użytkownika.
- przegląd listy graczy - przegląd jest intuicyjny, dodałabym opcję przechodzenia do konkretnej strony (idź do) listy, co ułatwiłoby jej przeglądanie.
- sortowanie graczy według poszczególnych kolumn - opcja sortowania mogłaby być bardziej widoczna, na pierwszy rzut oka wydaje się, że jej w ogóle nie ma. Przydatna mogłaby być też opcja sortowania wg daty dodania gracza do bazy.
- generowanie listy graczy do pliku .csv - opcja intuicyjna.
- drukowanie listy graczy - opcja intuicyjna.
- ustawianie widoku kolumn tabeli - działanie intuicyjne
- filtrowanie po danych z tabeli - działanie intuicyjne.

<b>3. Interfejs aplikacji</b>

Wygląd aplikacji jest bardzo prosty, wręcz zbyt prosty (wygląda na stronę sprzed 20 lat), nie do końca mi się to podoba.

<b>4. Intuicyjność aplikacji</b>

Aplikacja pod wieloma względami nie jest intuicyjna, po pierwszym zapoznaniu się z aplikacją ciężko się było zorientować, gdzie są poszczególne opcje. 

Jak wcześniej pisałam w podpunkcie 2, samo dodanie meczu czy wygenerowanie raportu nie było trudne, ale już znalezienie kategorii mecze i raporty nie było oczywiste. 

Tak samo dodanie nowego gracza jest średnio intuicyjne, znajduje się ono co prawda na głównej stronie, ale w kategorii "linki pomocnicze" co według mnie mnie sugeruje, że nie jest to jedna z najważniejszych funkcjonalności aplikacji. 

We wszystkich trzech podstronach (Gracze, Mecze, Raporty) brakuje opcji przejrzenia informacji bez konieczności edycji. Na przykładzie gracza: chcąc przejrzeć informacje o zawodniku (wzrost, rok urodzenia, osiągnięcia, poziom rozgrywek itd.) jednocześnie włącza się edycja zawodnika co może użytkownika aplikacji dezorientować. Dodatkowo "przymusowa" edycja sprawia, że użytkownik może przez przypadek zmienić lub wprowadzić nowe dane o zawodniku, które są błędne itp.

Najmniej intuicyjne jest dodawanie akcji, które miały miejsce podczas meczu (opcja "rozpocznij mecz"). Ze względu na bardziej złożony sposób dodania informacji, użytkownik bez instrukcji może mieć trudności z tą opcją.

<b>5. Błędy</b>

- <b>Strona główna: </b>

 W okienku aktywność literówka - napisane jest aktywnosć zamiast aktywność.
 
- Dodaj gracza:

pole  "telefon" - brak odpowiedniego formatu pola, możliwość dodania cyfr bez realnego limitu, możliwość dodania liter.

pole "waga" - brak odpowiedniego formatu pola, możliwość dodania ujemnej masy ciała, możliwość dodania cyfr bez realnego limitu.

pole "wzrost" - brak odpowiedniego formatu pola, możliwość dodania ujemnego wzrostu, możliwość dodania cyfr bez realnego limitu.

pole "data urodzenia" - brak ustawionego limitu na realny wiek gracza; można ustawić datę urodzenia na np. 1800 rok a także datę z przyszłości (np. 2024 r.)

opcja "dodaj język" - możliwość dodania kolejnego recordu "Języki", pomimo tego, że wcześniejszy record "Języki" pozostał pusty.

opcja "dodaj link z youtube" - możliwość dodania kolejnego recordu "link do youtube", pomimo tego, że wcześniejszy record "link do youtube" pozostał pusty.

widoczne jest angielskie "submit" i "clear" pomimo wybranego języka polskiego.
 
- Dodaj mecz:

pole "Zdobyte gole" - brak odpowiedniego formatu pola, możliwość dodania cyfr bez realnego limitu.

pole "Stracone gole" - brak odpowiedniego formatu pola, możliwość dodania cyfr bez realnego limitu.

pole "Czas gry" - brak odpowiedniego formatu pola, możliwość dodania ujemnego czasu gry, możliwość dodania cyfr bez realnego limitu.

pole "Data" - brak odpowiedniego formatu pola, możliwość dodania daty z przyszłości.

- Dodaj raport:

Obowiązek dodania województwa w zakładce Gracz, inaczej raport się nie wygeneruje. Podczas dodawania gracza nie ma informacji, że określenie województwa jest koniecznym działaniem. W raporcie informacja o województwie się nie pojawia, więc ten wymóg wydaje się być niepotrzebny podczas generowanai raportu.

- Edytuj raport:

Pomimo wybranego języka polskiego, przycisk "zapisz" jest w języku angielskim (save).

- Rozpocznij mecz:

Możliwe jest ustawienie więcej niż 4 połów rozgrywki, co nie jest realną ilością połów podczas meczu piłki nożnej (4 z uwzględnieniem dogrywki).

-Gracze:

Opcja sortowania, opcja pobrania CSV, opcja druku, ustawiania widoczności kolumn oraz filtrowanie tabeli są w języku angielskim, pomimo tego, że wybrany jest język polski

