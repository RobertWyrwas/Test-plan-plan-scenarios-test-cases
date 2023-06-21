**TestLink TEST PLAN MANAGEMENT** 

Mój przykładowy Plan Testów dla portalu **Booking.com** (z własnym komentarzem). 


**1. WSTĘP**

Głównym celem działań testowych jest dostarczenie interesariuszom informacji o jakości testowanego produktu.
W przygotowanym dokumencie zostały zebrane kluczowe informacje na temat działań testowych.
Zostały wyszczególnione wszystkie komponenty oprogramowania, które zostaną poddane wyryfikacji oraz typy testów jakie zostaną przeprowadzone.
 
_<<Wstęp powinien zawierać główne cele przeprowadzanych testów, które będziemy wykonywać: głównym celem może być np. dostarczenie interesariuszom informacji o przeprowadzonych testach oraz ich wynikach jak i to czy produkt nadaje się do wdrożenia produkcyjnego czy też nie. 
Wstęp może zawierać informacje dotyczące typów testów jakie wybraliśmy, jakie komponenty będą poddawane testowaniu itd.
Struktura Planu Testów może być odgórnie ustalona lub może występować względna dowolność w jej tworzeniu, w zależności od specyfiki pracy w danej firmie.
Dobrze, aby wstęp zawierał również ograniczenia zasobowe i budżetowe.>>_


**2. ZAKRES TESTÓW**

**Realizowane typy testów:**

•	Jednostkowe

•	Integracyjne

•	Funkcjonalne

•	Użyteczności

•	Dostępności

•	Wydajnościowe

•	Bezpieczeństwa

**Typy testów, które nie będą przeprowadzane:**

•	Testy automatyczne - ze względu na brak budżetu

_<<Zakres testów powinien również zawierać również typy testów, które nie będą realizowane z różnych względów np. ograniczony budżet, brak dostępu do niektórych wymaganych oprogramowań, brak kompetencji do realizacji niektórych typów testów bądź ograniczony czas.>>_

 
**3. PRZEDMIOTY TESTÓW**

**Komponenty, które zostaną poddane testom to:**

•	    Komponent logiki biznesowej (np. klasa obsługująca rezerwacje)

•	    Komponent dostępu do bazy danych (np. moduł obsługujący zapis i odczyt danych)

•	    Interfejs API (np. REST API dla komunikacji z innymi systemami)

•	    Komponenty współpracujące z zewnętrznymi usługami (np. moduł płatności)

•	    Moduł rejestracji użytkownika

•	    Moduł wyszukiwania ofert

•	    Moduł rezerwacji i potwierdzenia

•	    Moduł nawigacji i wyszukiwania informacji

•	    Moduł obsługi formularzy i walidacji danych

•	    Moduł responsywności strony na różnych urządzeniach

•	    Moduł obsługi czytników ekranowych

•	    Moduł skalowalności czcionek

•	    Moduł zapewnienia kontrastu kolorów

•	    Moduł odpowiedzialny za przetwarzanie żądań i generowanie odpowiedzi

•	    Moduł obsługujący równoczesne zapytania od wielu użytkowników

•	    Moduł uwierzytelniania i autoryzacji użytkowników

•	    Moduł zabezpieczeń przed atakami (np. SQL injection, cross-site scripting)

•	    Moduł odpowiedzialny za ochronę danych użytkowników


**4. KRYTERIA ZALICZENIA / NIEZALICZENIA TESTÓW**

_<<Punkty, które z góry określają kiedy nasze testy zostaną ukończone pomyślnie lub nie np:>>_

•	Minimalne pokrycie kodu przez testy jednostkowe, na przykład 80% linii kodu

•	Wszystkie przypadki testowe dla funkcjonalności są pomyślnie wykonane bez wystąpienia błędów.

•	Czas odpowiedzi serwera nie przekraczając 700ms

<< Powyższe kryteria to zaledwie kilka przykładami. Przy tworzeniu kryteriów, te zawsze powinny być dostosowane do konkretnej sytuacji i wymagań danego projektu.>>


**5. KRYTERIA WEJŚCIA / WYJŚCIA**

**1. Kryteria wejścia:**
       
•	Zakończona jest faza implementacji wyszukiwarki.

•	Ukończony proces integracji zewnętrznych usług.

•	Skompletowane dane testowe, w tym przykładowe rezerwacje, profile użytkowników itp.

•	Działające i skonfigurowane środowisko testowe

•	Dostęp do działającej i skonfigurowanej maszyny wirtualnej

**2. Kryteria wyjścia:**
       
•	Wszystkie przypadki testowe zostały zakończone pomyślnie

•	Komponent spełnia wszystkie ustalone założenia z załączonej dokumentacji

 
**6. LISTA WYMAGAŃ FUNKCJONALNOŚCI DO PRZETESTOWANIA**

Załączenie wszystkich dokumentacji, user stories, scenariuszy itp.

<<_Przykładowa lista powinna zawierać szczegółowe opisy poszczególnych funkcjonalności lub przypadków użycia, które będą poddane testom np:_>>

•	    Nazwa funkcjonalności: Wymienienie nazwy lub opisu konkretnej funkcjonalności, która będzie testowana np. "Funkcjonalność: Logowanie użytkownika/Wyszukiwanie produktu itp." Wymagania funkcjonalne: Weryfikacja poprawności danych logowania, obsługa różnych typów kont użytkowników (np. administrator, użytkownik zwykły), oczekiwane zachowanie po niepoprawnym logowaniu.)
 
•	    Opis funkcjonalności: Szczegółowy opis, co dana funkcjonalność ma realizować i jakie oczekiwane rezultaty powinny być osiągnięte np. "Opis: Umożliwia użytkownikowi zalogowanie się do systemu przy użyciu unikalnych danych uwierzytelniających./Umożliwia użytkownikowi wyszukanie pożądanego produktu"
 
•	    Wymagania funkcjonalne: Wymienienie konkretnych wymagań związanych z funkcjonalnością, które zostaną poddane testom. Mogą to być wymagania dotyczące   interakcji z użytkownikiem, zachowania systemu w różnych scenariuszach, przetwarzania danych, zgodności z regulacjami itp.

_<<Przykładowe wymagania funkcjonalne dla wyszukiwarki booking.com mogą obejmować:>>_

**Wyszukiwanie lokalizacji:**

o	Umożliwienie użytkownikowi wprowadzenia miejsca docelowego (miasta, regionu, kraju) w formularzu wyszukiwania.

o	Obsługa wyszukiwania po nazwie hotelu lub atrakcji turystycznej.

o	Opcja filtrowania wyników wyszukiwania na podstawie kategorii, ceny, ocen użytkowników itp.

**Wyświetlanie wyników wyszukiwania:**

o	Prezentacja listy dostępnych hoteli, apartamentów lub innych obiektów noclegowych w wybranej lokalizacji.

o	Wyświetlanie informacji o każdym obiekcie, takich jak nazwa, lokalizacja, oceny, zdjęcia, dostępność pokoi itp.

o	Wyświetlanie cen i dostępnych ofert dla różnych dat pobytu.

**Rezerwacja:**

o	Umożliwienie użytkownikowi wyboru preferowanej daty zameldowania i wymeldowania.

o	Zapewnienie możliwości wyboru preferowanej liczby gości i rodzaju pokoju.

o	Przejście do procesu rezerwacji, w tym wprowadzenie danych osobowych, danych płatności itp.

**Zarządzanie rezerwacjami:**

o	Udostępnienie użytkownikowi panelu zarządzania rezerwacjami, gdzie można przeglądać, modyfikować lub anulować dokonane rezerwacje.

o	Wysyłanie potwierdzeń rezerwacji na adres e-mail użytkownika.

o	Wyświetlanie historii rezerwacji i dostępnych informacji kontaktowych do hoteli.

**Oceny i opinie:**

o	Pozwolenie użytkownikom na wystawianie ocen i opinii na temat zarezerwowanych obiektów.

o	Wyświetlanie ocen i opinii innych użytkowników, aby pomóc w podejmowaniu decyzji rezerwacyjnych.

**Obsługa wielu języków i walut:**

o	Zapewnienie możliwości korzystania z wyszukiwarki w różnych językach.

o	Konwersja cen na różne waluty zgodnie z preferencjami użytkownika.

**Intuicyjny interfejs użytkownika:**

o	Zapewnienie prostego i intuicyjnego interfejsu użytkownika, który umożliwia łatwe wyszukiwanie, filtrowanie i rezerwację.
 
**Przypadki testowe:** _<<Określenie przypadków testowych lub scenariuszy, które zostaną użyte do przetestowania danej funkcjonalności. Mogą to być opisy kroków testowych, oczekiwanych rezultatów i danych testowych, które będą wykorzystane:>>_

**1.	Przypadek testowy: Wyszukiwanie lokalizacji**
   
Kroki testowe:

1.	Otwórz stronę główną wyszukiwarki booking.com.
2.	Wprowadź miejsce docelowe w polu wyszukiwania.
3.	Wybierz odpowiednią lokalizację z listy sugerowanych wyników.
4.	Kliknij przycisk "Szukaj".
   
Oczekiwany rezultat:
Wyświetlenie wyników wyszukiwania zawierających hotele i obiekty noclegowe w wybranej lokalizacji.

**2.	Przypadek testowy: Filtrowanie wyników wyszukiwania**

Kroki testowe:

0.	Wykonaj wyszukiwanie dla określonej lokalizacji.
1.	Zastosuj filtr według wybranej kategorii, ceny, oceny lub innego kryterium.
2.	Przejrzyj wyniki wyszukiwania po zastosowaniu filtrów.
   
Oczekiwany rezultat:

Wyświetlenie tylko tych wyników, które spełniają wybrane kryteria filtrów.

**4.	Przypadek testowy: Rezerwacja pokoju**

Kroki testowe:

0.	Wykonaj wyszukiwanie dla określonej lokalizacji i daty pobytu.
1.	Wybierz konkretny obiekt noclegowy z wyników wyszukiwania.
2.	Wybierz preferowany rodzaj pokoju i liczbę gości.
3.	Przejdź do procesu rezerwacji i wprowadź dane osobowe i płatności.
4.	Potwierdź rezerwację.
   
Oczekiwany rezultat:

Potwierdzenie rezerwacji z wyświetleniem szczegółów dotyczących daty pobytu, ceny, danych kontaktowych obiektu noclegowego itp.

**4.	Przypadek testowy: Zarządzanie rezerwacjami**

Kroki testowe:

0.	Zaloguj się na swoje konto w wyszukiwarce booking.com.
1.	Przejdź do sekcji zarządzania rezerwacjami.
2.	Wybierz konkretną rezerwację do przeglądu lub modyfikacji.
3.	Sprawdź, czy można przeglądać szczegóły rezerwacji, dokonać zmian (jeśli dozwolone) lub anulować rezerwację.
   
Oczekiwany rezultat:

Wyświetlanie dokładnych informacji dotyczących rezerwacji oraz możliwość modyfikacji lub anulowania rezerwacji (jeśli to możliwe).

**5.	Przypadek testowy: Oceny i opinie**

Kroki testowe:

0.	Znajdź zarezerwowany obiekt noclegowy.
1.	Sprawdź, czy można wystawić ocenę i opinię na temat tego obiektu.
2.	Wystaw ocenę i opinię dla danego obiektu.
3.	Sprawdź, czy oceny i opinie są wyświetlane w odpowiednich miejscach i czy można przeglądać oceny innych użytkowników.
   
Oczekiwany rezultat:

Możliwość wystawienia oceny i opinii dla zarezerwowanego obiektu oraz wyświetlanie ocen i opinii innych użytkowników.
 
**Priorytetyzacja:** Określenie priorytetów dla poszczególnych funkcjonalności w kontekście testowania. Może to obejmować wysoki priorytet dla krytycznych funkcjonalności, które mają duże znaczenie dla systemu lub niski priorytet dla funkcjonalności mniej istotnych.

 
**7. ŚRODOWISKO TESTOWE**

•	Testowy serwer (Development)

•	System Windows 10 Home 64 bit

•	Przeglądarki biorące udział w testach: 

Firefox 114.0.1

Edge 114.0.1823.51

Chrome 114.0.5735.134

Opera 99.0.4788.77
 
_<<W innych przypadkach możemy zawrzeć informacje takie jak:
Wersje oprogramowania, które będą wykorzystywane w środowisku testowym, serwery baz danych czy też frameworki testowe. Wskazanie konkretnych wersji jest istotne dla zapewnienia powtarzalności testów.
Konfiguracje sprzętowe: jeśli istnieją określone wymagania dotyczące sprzętu, takie jak procesor, pamięć RAM, dysk twardy, karta graficzna, należy je uwzględnić. Na przykład, jeśli aplikacja jest wrażliwa na wydajność, można określić minimalne wymagania sprzętowe, które muszą zostać spełnione w celu przeprowadzenia testów.
Serwery i usługi zewnętrzne: jeżeli aplikacja korzysta z zewnętrznych usług, takich jak bazy danych, serwisy sieciowe, usługi chmurowe, należy je uwzględnić w środowisku testowym. Wskazówki dotyczące konfiguracji i dostępności tych usług mogą być istotne dla testów integracyjnych lub testów wydajnościowych.>>_

 
**8. HARMONOGRAM TESTÓW**
 
      **1. Przeprowadzenie testów jednostkowych: **
      
•	Sprawdzanie, czy funkcje lub metody zwracają oczekiwane wartości w zależności od różnych przypadków testowych - 2h

•	Testowanie funkcji lub modułów z wykorzystaniem danych testowych na granicach lub w przypadkach skrajnych - 2h

•	Weryfikacja poprawności interakcji między różnymi jednostkami kodu - 3h

      **2. Przeprowadzenie testów funkcjonalnych:**
      
•	weryfikacja funkcjonalności w oparciu o user story - 3h

•	wykonanie wcześniej zaprojektowanych przypadków testowych - 1h

•	weryfikacja warstwy backendowej - 2h

•	Przetestowanie procesu rejestracji nowego użytkownika - 2h

•	Weryfikacja poprawności wyszukiwania i filtracji ofert - 3h

•	Testowanie funkcji rezerwacji i potwierdzenia - 2h

     ** 3. Przeprowadzenie testów wydajnościowych:**
     
•	weryfikacja średniego czasu odpowiedzi - 1h

•	weryfikacja maksymalnej ilości requestów przy jakiej wyszukiwarka działa stabilnie -1h

     ** 4.Przeprowadzenie testów integracyjnych:**
     
1.	Weryfikacja poprawnego przekazywania danych między komponentami: 2h
2.	Testowanie integracji zewnętrznych usług (np. płatności, mapy): 3h
3.	Weryfikacja poprawnej komunikacji między serwerem a bazą danych - 2h
   
    ** 5.Przeprowadzenie testów użyteczności:**
  	
1.	Ocena łatwości nawigacji po stronie i odnajdywania informacji - 2h
2.	Testowanie czytelności i zrozumiałości treści oraz etykiet formularzy - 3h
3.	Sprawdzanie responsywności strony na różnych urządzeniach i przeglądarkach - 2h
   
      **6.Przeprowadzenie testów dostępności i bezpieczeństwa: **
  	
1.	Weryfikacja zgodności strony z wytycznymi dostępności WCAG - 3h
2.	Przeprowadzenie testów penetracyjnych w celu wykrycia potencjalnych luk w zabezpieczeniach - 4h
3.	Sprawdzanie czy strona jest odporna na ataki takie jak SQL injection i cross-site scripting (XSS) - 2h

   
**9. RAPORT Z TESTÓW**

•	Lista zrealizowanych przypadków testowych wraz ze statusami
•	Raport defektów
•	Raport z testów zgodności
•	Pomiary z testów wydajnościowych
•	Inne raporty z testów

 
**10. LISTA NARZĘDZI**

•	Jmeter
•	TestLink
•	Postman
•	Jira
•	Browserstack
 
**11. RYZYKA I PROBLEMY**

_<< W tym punkcie możemy uwzględnić różne czynniki, które mogą wpływać na proces testowania i jego rezultaty. >>_
Przykładowe zagrożenia:
•	    Opóźnienia w dostawie oprogramowania: ryzyko opóźnień w dostarczeniu komponentów oprogramowania, które są wymagane do przeprowadzenia testów.

•	    Niedostępność środowiska testowego: ryzyko braku dostępu do odpowiedniego środowiska testowego, takiego jak serwery, bazy danych, sieci, co może utrudnić przeprowadzenie testów.

•	    Niekompletność lub niejasność wymagań: ryzyko braku jasno zdefiniowanych wymagań, co może prowadzić do trudności w tworzeniu przypadków testowych i ocenie sukcesu testów.

•	    Brak zasobów ludzkich: ryzyko niedostatecznej liczby lub odpowiednich umiejętności członków zespołu testowego, co może wpływać na efektywność testów.

•	    Błędy w dokumentacji: ryzyko obecności błędów, niejasności lub nieaktualnych informacji w dokumentacji projektowej, co może prowadzić do testowania nieodpowiednich funkcjonalności lub prowadzić do niezgodności z oczekiwaniami.

•	    Problemy z integracją: ryzyko trudności w integracji różnych komponentów lub modułów systemu, co może prowadzić do błędów w interakcji między nimi.

•	    Ograniczenia czasowe: ryzyko braku wystarczającego czasu na przeprowadzenie pełnego zakresu testów lub na dokładne badanie problemów znalezionych podczas testowania.

•	    Problemy wydajnościowe: ryzyko wystąpienia problemów wydajnościowych, takich jak spowolnienia lub awarie systemu podczas obciążenia lub w warunkach skrajnych.

•	    Zależności od zewnętrznych dostawców: ryzyko opóźnień lub problemów związanych z dostępnością zewnętrznych usług lub komponentów, które są niezbędne do przeprowadzenia testów.

•	    Brak odpowiedniej dokumentacji: ryzyko braku wystarczającej dokumentacji technicznej lub brak dostępu do niej, co może utrudnić zrozumienie i testowanie systemu.

 
**12. ZARZĄDZANIE INCYDENTAMI I BŁĘDAMI**

•	W procesie testowym każdy wykryty błąd powinien być odpowiednio zaraportowany do systemu Jira.

•	Uwzględnienie priorytetu błędu, osoby przypisanej (developera), komponentu którego dotyczy problem.

•	Zgodnie z przyjętym flow przez naszą organizację, taki problem powinien zostać naprawiony przez developera i trafić do retestów.

 
**13. ROLE I ODPOWIEDZIALNOŚĆ**

1.	Anna Nowak:
   
o	Przeprowadzenie testów funkcjonalnych: weryfikacja funkcjonalności w oparciu o user story

o	Testowanie funkcji rezerwacji i potwierdzenia

2.	Michał Kowalski:
   
Przeprowadzenie testów jednostkowych: 

o Sprawdzanie, czy funkcje lub metody zwracają oczekiwane wartości w zależności od różnych przypadków testowych

o Testowanie funkcji lub modułów z wykorzystaniem danych testowych na granicach lub w przypadkach skrajnych

3.	Robert Wyrwas:
   
Przeprowadzenie testów wydajnościowych: 

o Weryfikacja średniego czasu odpowiedzi

o Weryfikacja maksymalnej ilości requestów przy jakiej wyszukiwarka działa stabilnie

4.	Piotr Jankowski:
   
o	Przeprowadzenie testów integracyjnych:

o Weryfikacja poprawnego przekazywania danych między komponentami

o Testowanie integracji zewnętrznych usług (np. płatności, mapy)

5.	Magdalena Woźniak:
   
Przeprowadzenie testów użyteczności:

o Ocena łatwości nawigacji po stronie i odnajdywania informacji

o Sprawdzanie responsywności strony na różnych urządzeniach i przeglądarkach

6.	Tomasz Kaczmarek:
   
o	Przeprowadzenie testów dostępności i bezpieczeństwa:

o Weryfikacja zgodności strony z wytycznymi dostępności

o Przeprowadzenie testów penetracyjnych w celu wykrycia potencjalnych luk w zabezpieczeniach

