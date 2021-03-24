# Specyfikacja:
## Dokument zawiera wstępna specyfikacje projektu: Aplikacja webowa do przeglądania informacji na temat książek.
### Spis treści
[Cel](#Cel)

[Opis](#Opis)

[Diagram UML](#Diagram-UML)

[Szkic wstępny interfejsu](#Szkic-wstępny-interfejsu)

[Referencje](#Referencje)

[Kryteria zmiany specyfikacji](#Kryteria-zmiany-specyfikacji)

[Proces śledzenia pracy](#Proces-śledzenia-pracy)

[Wymagania funkcjonalne](#Wymagania-funkcjonalne)

[Wymagania niefunkcjonalne](#Wymagania-niefunkcjonalne)

[Technologie](#Technologie)



## Cel
Celem projektu jest napisanie witryny internetowej, której tematyka kręci się wokół książek. Witryna ma umożliwiać użytkownikowi wiele funkcji, które w jakiś sposób związane są z tematyką literatury, dzięki tym funkcjonalnością użytkownik będzie mógł sprawdzić wiele interesujących go rzeczy w sposób szybki i prosty.
## Opis
#### 	a.	Opis ogólny
System będzie zawierał witrynę internetową w której będzie mógł funkcjonować użytkownik i wykonywać polecenia dla systemu. System będzie natomiast operował na bazie danych oraz informacjach pobranych z Internetu. Do pobierania informacji zamierzamy wykorzystać internetowe API.  Natomiast sam użytkownik będzie musiał się zarejestrować w naszym systemie aby móc z niego korzystać.
#### 	b.	Środowisko
Aplikacja będzie działać w oparciu o MVC, gdzie umieścimy w samej aplikacji wszystkie potrzebne nam funkcjonalności. Całość napiszemy w języku c# przy użyciu oprogramowania .NET Core.
## Diagram UML
![Diagram UML Use Case](/img/UseCaseDiagram.png)
## Szkic wstępny interfejsu
![Szkic interfejsu](/img/Szkic.png)
## Referencje
Repozytorium na githubie: [GitHub](https://github.com/MichealRG/WebApp-CheckInfoAboutBooks)

System zarządzania projetkem: [DevOps Azure](https://dev.azure.com/mk054433/Aplikacja%20webowa%20zbieraj%C4%85ca%20informacje%20o%20ksi%C4%85%C5%BCkach)
## Kryteria zmiany specyfikacji
Specyfikacja z czasem może ewoluować. Zmiany w specyfikacji mogą pojawić się w sytuacjach takich jak:
*	Obecny sposób działania, się nie sprawdzi – będzie skomplikowany i niejasny 
*	Niezbędna funkcjonalność. Zabraknie nam funkcjonalności z powodu określonej już specyfikacji
*	Ewolucja oprogramowania. Ponieważ trendy, systemy, api, formaty, wzorce potrafią się zmieniać, a my w związku z tym możemy zastanowić się, czy taka zmiana wpływa na nasz projekt.
## Proces śledzenia pracy
*	GitHub jako źródło informacji o projekcie, postępach, dostępnych funkcjonalnościach.
*	Praca będzie dzielona na branche, gdzie jeden branch będzie jedną funkcjonalnością
*	Main – obecna stabilna wersja, gałąź główna projektu
*	Nowe funkcje będą wykonywane w branachach, które po wykonaniu będą łączone w odpowiedni branch.
*	Gdy funkcja zostaje ukończona zostanie scalona z główną gałezią
## Wymagania funkcjonalne:
1.	System logowania i rejestracji 
	- [ ]	Utworzenie własnego konta
	- [ ]	Możliwość zalogowania się na nasze konto z naszymi informacjami
2.	Ustawienia użytkownika
	- [ ]	Użytkownik poprzez wejście w odpowiednią zakładkę jest w stanie zmienić informacje dotyczące jego konta. Informacje takie jak np. e-mail, nazwa użytkownika czy hasło.
3.	Zakładka z własną biblioteczka
	- [ ]	Dodanie do biblioteczki książki którą właśnie czytam/ przeczytałem
	- [ ]	Zapisywać swoje własne uwag odnośnie książki,
	- [ ]	Zapisanie liczba stron którą przeczytałem,
	- [ ]	Możliwość określenia planu czytelniczego,
	- [ ]	Możliwość grupowania książek w nasze własne grupy
	- [ ]	Wystawienie oceny danej pozycji,
	- [ ]	Możliwość oznaczeni książki jako wartej przeczytania.
4.	System umożliwiający przegląd informacji na temat książek
	- [ ]	Informacje będą pobierane z Internetu
	- [ ]	Informacje które zostaną pobrane to np. autor, wydawca, tytuł, język, rok wydania.
	- [ ]	Użytkownik otrzyma informacje dotyczące danej frazy wyszukiwania.
	- [ ]	Umieszczanie innych mechanizmów
5.	Historia wyszukiwania użytkownika
	- [ ]	Możliwość przeglądu ostatnio wyszukanych pozycji.
6.	System wyświetlania informacji o obiektach związanych z książkami 
	- [ ]	Pobranie informacji o obiektach w pobliżu naszej lokalizacji
	- [ ]	Wyświetlenie obiektów związanych w jakiś sposób z książkami z naszej okolicy
	- [ ]	Jeżeli możliwe będą do pozyskania informacje odnośnie danych obiektów, także zostaną wyświetlone.
7.	Ranking najlepiej ocenianych książek
	- [ ]	System sprawdza, które książki zostały ocenione najwyżej przez użytkowników i wyświetla je w perspektywie top 100 książek.
## Wymagania niefunkcjonalne:
1.	Aplikacja będzie podzielona na fronted – widok i backend - controller
2.	Aplikacja powinna być intuicyjna i prosta w obsłudze
3.	System logowania powinien odpowiednio walidować hasła i konta
4.	System powinien mieć dostęp do bazy danych 
5.	System powinien umożliwiać nawigowanie po stronie webowej przy pomocy klawiatury
6.	Przetestowanie aplikacji testami jednostkowymi i integracyjnymi
7.	Responsywność aplikacji
## Technologie
1.	.NET Core
2.	Język programowania C#
3.	Relacyjna baza danych SQL z użyciem entity frameworka
4.	Sellenium – testowanie
5.	Docker – automatyzacja developmentu



