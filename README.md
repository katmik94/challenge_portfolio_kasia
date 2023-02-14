# Task 1
## Subtask 1
9 punktów
## Subtask 3
Stawiam pierwsze kroki w kierunku zostania testerką i zdecydowałam się na wzięcie udziału w Challenge Portfolio, ponieważ jest to świetny sposób na zdobycie wiedzy, a także na stworzenia właśnie swojego portfolio. Podczas wykonywania zadań bedę mogła też utrwalić sobie i sprawdzić wiedzę w praktyce, co jest według mnie najlepszym sposobem na naukę 🙂. Cotygodniowe zadania są też dla mnie dodatkową motywacją do systematycznej nauki i pracy.

Moim celem jest wykorzystanie zdobytej podczas projektu wiedzy i powstałego portfolio do stania się w przyszłości zawodowym testerem oprogramowania.
## Subtask 4
<b>1. Do czego służy aplikacja?</b>

Aplikacja służy skautom do dodawania, przeglądania zawodników i śledzenia ich umiejętności, do sprawdzania ich poziomu gry podczas meczów. Korzystają przy tym z raportów, które można wygenerować dla zawodników.

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
- ustawianie widoku kolumn tabeli - działanie intuicyjne.
- filtrowanie po danych z tabeli - działanie intuicyjne.

<b>3. Interfejs aplikacji</b>

Wygląd aplikacji jest bardzo prosty, wręcz zbyt prosty (wygląda na stronę sprzed 20 lat), nie do końca mi się to podoba.

<b>4. Intuicyjność aplikacji</b>

Aplikacja pod wieloma względami nie jest intuicyjna, po pierwszym zapoznaniu się z aplikacją ciężko się było zorientować, gdzie są poszczególne opcje. 

Jak wcześniej pisałam w podpunkcie 2, samo dodanie meczu czy wygenerowanie raportu nie było trudne, ale już znalezienie kategorii "Mecze" i "Raporty" nie było oczywiste. 

Tak samo dodanie nowego gracza jest średnio intuicyjne, znajduje się ono co prawda na głównej stronie, ale w kategorii "linki pomocnicze" co według mnie może błędnie sugerować, że nie jest to jedna z najważniejszych funkcjonalności aplikacji. 

We wszystkich trzech podstronach (Gracze, Mecze, Raporty) brakuje opcji przejrzenia informacji bez konieczności edycji. Na przykładzie gracza: chcąc przejrzeć informacje o zawodniku (wzrost, rok urodzenia, osiągnięcia, poziom rozgrywek itd.) jednocześnie włącza się edycja zawodnika, co może użytkownika aplikacji dezorientować. Dodatkowo "przymusowa" edycja sprawia, że użytkownik może przez przypadek zmienić lub wprowadzić nowe dane o zawodniku, które są błędne itp. Dokładnie tak samo jest w przypadku ppreglądania meczu, czy przeglądania raportu.

Najmniej intuicyjne jest dodawanie akcji, które miały miejsce podczas meczu (opcja "rozpocznij mecz"). Ze względu na bardziej złożony sposób dodania informacji, użytkownik bez instrukcji może mieć trudności z tą opcją.

<b>5. Błędy</b>

<b>Strona główna: </b>

 W okienku aktywność literówka - napisane jest aktywnosć zamiast aktywność.
 
<b>Dodaj gracza:</b>

-pole  "telefon" - brak odpowiedniego formatu pola, możliwość dodania cyfr bez realnego limitu, możliwość dodania liter.

-pole "waga" - brak odpowiedniego formatu pola, możliwość dodania ujemnej masy ciała, możliwość dodania cyfr bez realnego limitu.

-pole "wzrost" - brak odpowiedniego formatu pola, możliwość dodania ujemnego wzrostu, możliwość dodania cyfr bez realnego limitu.

-pole "data urodzenia" - brak ustawionego limitu na realny wiek gracza; można ustawić datę urodzenia na np. 1800 rok a także datę z przyszłości (np. 2024 r.)

-opcja "dodaj język" - możliwość dodania kolejnego recordu "Języki", pomimo tego, że wcześniejszy record "Języki" pozostał pusty.

-opcja "dodaj link z youtube" - możliwość dodania kolejnego recordu "link do youtube", pomimo tego, że wcześniejszy record "link do youtube" pozostał pusty.

-widoczne jest angielskie "submit" i "clear" pomimo wybranego języka polskiego.
 
<b>Dodaj mecz: </b>

-pole "Zdobyte gole" - brak odpowiedniego formatu pola, możliwość dodania cyfr bez realnego limitu.

-pole "Stracone gole" - brak odpowiedniego formatu pola, możliwość dodania cyfr bez realnego limitu.

-pole "Czas gry" - brak odpowiedniego formatu pola, możliwość dodania ujemnego czasu gry, możliwość dodania cyfr bez realnego limitu.

-pole "Data" - brak odpowiedniego formatu pola, możliwość dodania daty z przyszłości.

<b>Dodaj raport:</b>

Raport się nie wygeneruje jeśli nie ma dodanego województwa w zakładce "Gracz". Podczas dodawania gracza nie ma informacji, że określenie województwa jest koniecznym działaniem. W raporcie informacja o województwie się nie pojawia, więc ten wymóg wydaje się być niepotrzebny podczas generowania raportu.

<b>Edytuj raport:</b>

Pomimo wybranego języka polskiego, przycisk "zapisz" jest w języku angielskim (save).

<b>Rozpocznij mecz:</b>

Możliwe jest ustawienie więcej niż 4 połów rozgrywki, co nie jest realną ilością połów podczas meczu piłki nożnej (4 z uwzględnieniem dogrywki).

<b>Gracze:</b>

Opcja sortowania, opcja pobrania CSV, opcja druku, ustawiania widoczności kolumn oraz filtrowanie tabeli są w języku angielskim, pomimo tego, że wybrany jest język polski.

## Subtask 5

Biorę udział w tym subtasku, zostałam dodana do grupy :smile:


# Task 2

## Subtask 1

Link do pierwszego subtasku:

https://docs.google.com/document/d/1lFrcQnkL0tfQyJOfAip0-ALIMlv22lzf7JPDO7nas9U/edit

## Subtask 2

Link do drugiego subtasku:

https://docs.google.com/document/d/1femvFWpcguYLerf89ZMv0LsAXxImXt-qYEb7O4cGF-Y/edit

## Subtask 3

-Przypadki testowe służą do sprawdzenia poprawności działania programu lub aplikacji. 

-Lista przypadków testowych zawiera różne scenariusze, które mają na celu wykrycie błędów lub nieoczekiwanych zachowań w oprogramowaniu. 

-Tworzenie przypadków testowych pozwala na wczesne wykrycie i naprawienie błędów, co zwiększa jakość i niezawodność oprogramowania. 

-Tworzenie przypadków na podstawie kryteriów akceptacji pozwala na zaprojektowanie testów a następnie planów testów, nawet kiedy oprogramowanie nie jest jeszcze dostarczone. 

-Przypadki testowe są również przydatne podczas regresji, ponieważ tworzą "bibliotekę" test case'ów i dzięki temu zmniejszają ryzyko pominięcia jakiegoś testu.


# Task 3
## Subtask 1
https://docs.google.com/document/d/1CU33KtPIRDph_Q7f0VV5Jb0H80Q40DM_kullRzv86QA/edit?usp=sharing

## Subtask 3
https://docs.google.com/document/d/1zqHJ6RolKDBCobI3daqani7bshEVXSpNGv9xuvSk-T0/edit?usp=sharing

# Task 4
## Subtask 2

https://docs.google.com/document/d/1bwRSvL8XKG7OYw-j-iOERg3Vu7D6Sr3KDZJCxnZJmRM/edit?usp=sharing

## Subtask 3

<i>1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?</i>

Aplikacja służy do kupowania lub sprzedaży przez użytkowników produktów nowych lub używanych, często lokalnie. 

<i>2. Kto ma być użytkownikiem końcowym aplikacji?</i>

Użytkownikiem końcowym aplikacji głównie jest osoba prywatna, która chce coś sprzedać lub kupić bez dodatkowych opłat.

<i>3. Czy według Ciebie aplikacja jest user friendly?</i>

Według mnie aplikacja jest user friendly. Interfejs nie jest skomplikowany, od pierwszego wejścia do aplikacji przemieszczanie się po niej jest dosyć intuicyjne, wiadomo w co gdzie klikać, jak wybierać kategorie, filtrować, jak dodać ogłoszenie, wejść w ustawienia. Przyciski szybkiego dostępu minimalistyczne, dobrze opisane, dobrze dopasowane do mojego telefonu. Ze względu na ograniczoną ilość barw aplikacja jest przyjazna w odbiorze i przejrzysta, uproszczone grafiki również bardzo przyjemne dla oka.

<i>4. Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?</i>

Aplikacja ogólnie bardzo dobrze funkcjonuje i bardzo dobrze się z niej korzysta. Jedną z rzeczy, jaką bym dodała jest możliwość filtrowania ogłoszeń u jednego sprzedawcy. Kiedy osoba sprzedająca ma dużo ofert, filtrowanie bardzo by ułatwiło w szukaniu u niego konkretnej rzeczy lub rzeczy z konkretnej kategori.

<i>5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?</i>
- Podczas testowania aplikacji internetowej jest możliwość skorzystania z DevTools, które dostarczają duzy zestaw narzędzi do testowania, natomiast przy testowaniu aplikacji natywnej nie ma takich narzędzi
- Podczas testowania aplikacji natywnej można zmieniać landscape z pionowego na poziomy, natomiast przy testowaniu aplikacji webowej nie ma takiej możliwości

# Task 5

## Subtask 1

<b>Zapytania, które poznałam:</b>

- SELECT
- FROM
- GO
- ON
- AS
- CREATE TABLE
- ORDER BY (ASC, chociaż ono nie jest obowiązkowe)
- ORDER BY DESC
- WHERE

<b>Operatory, które poznałam:</b>

![](https://tinypic.host/images/2023/02/14/operatory.png) 

## Subtask 3

<i>1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.</i>

SELECT*FROM actors ORDER BY surname 
![](https://tinypic.host/images/2023/02/14/1sql1.png) 
<i>2.Wyświetl film, który powstał w 2019 roku.</i>
<i>3.Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.</i>
Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$
Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.
Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.
Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
Wyświetl dane klienta, który nie ma podanego adresu email.
Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

