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
- INNER JOIN
- UPDATE
- ALTER TABLE
- UNION
- INSERT INTO

<b>Operatory, które poznałam:</b>

![](https://tinypic.host/images/2023/02/14/operatory.png) 

## Subtask 3

<i>1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.</i>

SELECT*FROM actors ORDER BY surname 

![](https://tinypic.host/images/2023/02/14/1sql1.png) 

<i>2.Wyświetl film, który powstał w 2019 roku.</i>

SELECT*FROM movies WHERE year_of_production='2019'

![](https://tinypic.host/images/2023/02/14/1sql2.png) 

<i>3.Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.</i>

SELECT*FROM movies WHERE year_of_production BETWEEN'1900'AND '1999'

![](https://tinypic.host/images/2023/02/14/sql3.png) 

<i>4.Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$</i>

SELECT title,price FROM movies WHERE price<7

![](https://tinypic.host/images/2023/02/14/sql4.png) 

<i>5.Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.</i>

SELECT*FROM actors WHERE actor_id >=4 AND actor_id <=7

![](https://tinypic.host/images/2023/02/14/sql5.png) 

<i> 6.Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.</i>

SELECT * FROM customers WHERE customer_id = 2 OR customer_id=4 OR customer_id=6

![](https://tinypic.host/images/2023/02/14/sql6.png) 

<i> 7.Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN. </i>

SELECT * FROM customers WHERE customer_id IN(1,3,5)

![](https://tinypic.host/images/2023/02/14/sql7.png) 

<i>8.Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.</i>

SELECT * FROM actors WHERE name LIKE 'An%'

![](https://tinypic.host/images/2023/02/14/sql8.png) 

<i>9.Wyświetl dane klienta, który nie ma podanego adresu email.</i>

SELECT * FROM customers WHERE email IS NULL

![](https://tinypic.host/images/2023/02/14/sql9.png) 

<i>10.Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.</i>

SELECT * FROM movies WHERE price>9 and movie_id BETWEEN 2 and 8

![](https://tinypic.host/images/2023/02/14/sql10.png) 

# Task 6

## Subtask 1

<i> 11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd.</i>

UPDATE customers SET surname='Miler' WHERE customer_id=3

![](https://tinypic.host/images/2023/02/21/sql11.png) 

<i> 12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej. </i>

SELECT sale.movie_id, customers.name, customers.email FROM sale INNER JOIN customers ON sale.customer_id=customers.customer_id WHERE movie_id='4'

![](https://tinypic.host/images/2023/02/21/sql12.png) 

<i>13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com </i>

UPDATE customers SET email = 'pati@mail.com' WHERE customer_id=4

![](https://tinypic.host/images/2023/02/21/sql13.png) 

<i>14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia). </i>

SELECT movies.title, customers.name, customers.surname FROM sale INNER JOIN customers ON sale.customer_id=customers.customer_id INNER JOIN movies ON sale.movie_id=movies.movie_id

![](https://tinypic.host/images/2023/02/21/sql14.png) 

<i>15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag </i>

ALTER TABLE customers ADD pseudonym varchar(255);

UPDATE customers SET pseudonym= 'Ols' WHERE customer_id=1; UPDATE customers SET pseudonym= 'Kal' WHERE customer_id=2; UPDATE customers SET pseudonym= 'Anr' WHERE customer_id=3; UPDATE customers SET pseudonym= 'Par' WHERE customer_id=4; UPDATE customers SET pseudonym= 'Mao' WHERE customer_id=5; UPDATE customers SET pseudonym= 'Nag' WHERE customer_id=6

![](https://tinypic.host/images/2023/02/21/sql15.png) 

<i>16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały. </i>

SELECT DISTINCT movies.title FROM sale INNER JOIN movies ON sale.movie_id=movies.movie_id

![](https://tinypic.host/images/2023/02/21/sql16.png) 

<i>17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION) </i>

SELECT name FROM customers UNION SELECT name FROM actors ORDER BY name ASC

![](https://tinypic.host/images/2023/02/21/sql17.png) 

<i>18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).</i>

UPDATE movies SET price=price+2.5 WHERE year_of_production>2000

![](https://tinypic.host/images/2023/02/21/sql18.png) 

<i>19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał </i>

SELECT actors.name, actors.surname, movies.title FROM cast INNER JOIN actors ON actors.actor_id=cast.actor_id INNER JOIN movies ON movies.movie_id=cast.movie_id WHERE cast.actor_id ='4'

![](https://tinypic.host/images/2023/02/21/sql19.png) 

<i>20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa </i>

INSERT INTO customers (customer_id, name, surname, email, pseudonym) VALUES ('7', 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa')

![](https://tinypic.host/images/2023/02/21/sql20.png) 

## Subtask 2

Otrzymałam 11/15 punktów.

![](https://tinypic.host/images/2023/02/21/wyniki.png)

## Subtask 3



