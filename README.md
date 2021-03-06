# Specyfikacja:
## Dokument zawiera wst臋pna specyfikacje projektu: Aplikacja webowa do przegl膮dania informacji na temat ksi膮偶ek. 馃摃
### Spis tre艣ci
[Cel](#Cel)

[Opis](#Opis)

[Diagram UML](#Diagram-UML)

[Szkic wst臋pny interfejsu](#Szkic-wst臋pny-interfejsu)

[Referencje](#Referencje)

[Kryteria zmiany specyfikacji](#Kryteria-zmiany-specyfikacji)

[Proces 艣ledzenia pracy](#Proces-艣ledzenia-pracy)

[Wymagania funkcjonalne](#Wymagania-funkcjonalne)

[Wymagania niefunkcjonalne](#Wymagania-niefunkcjonalne)

[Technologie](#Technologie)



## Cel
Celem projektu jest napisanie witryny internetowej, kt贸rej tematyka kr臋ci si臋 wok贸艂 ksi膮偶ek. Witryna ma umo偶liwia膰 u偶ytkownikowi wiele funkcji, kt贸re w jaki艣 spos贸b zwi膮zane s膮 z tematyk膮 literatury, dzi臋ki tym funkcjonalno艣ci膮 u偶ytkownik b臋dzie m贸g艂 sprawdzi膰 wiele interesuj膮cych go rzeczy w spos贸b szybki i prosty.
## Opis
#### 	a.	Opis og贸lny
System b臋dzie zawiera艂 witryn臋 internetow膮 w kt贸rej b臋dzie m贸g艂 funkcjonowa膰 u偶ytkownik i wykonywa膰 polecenia dla systemu. System b臋dzie natomiast operowa艂 na bazie danych oraz informacjach pobranych z Internetu. Do pobierania informacji zamierzamy wykorzysta膰 internetowe API.  Natomiast sam u偶ytkownik b臋dzie musia艂 si臋 zarejestrowa膰 w naszym systemie aby m贸c z niego korzysta膰.
#### 	b.	艢rodowisko
Aplikacja b臋dzie dzia艂a膰 w oparciu o MVC, gdzie umie艣cimy w samej aplikacji wszystkie potrzebne nam funkcjonalno艣ci. Ca艂o艣膰 napiszemy w j臋zyku c# przy u偶yciu oprogramowania .NET Core.
## Diagram UML
![Diagram UML Use Case](/img/UseCaseDiagram.png)
## Szkic wst臋pny interfejsu
![Szkic interfejsu](/img/Szkic.png)
## Referencje
Repozytorium na githubie: [GitHub](https://github.com/MichealRG/WebApp-CheckInfoAboutBooks)

System zarz膮dzania projetkem: [DevOps Azure](https://dev.azure.com/mk054433/Aplikacja%20webowa%20zbieraj%C4%85ca%20informacje%20o%20ksi%C4%85%C5%BCkach)
## Kryteria zmiany specyfikacji
Specyfikacja z czasem mo偶e ewoluowa膰. Zmiany w specyfikacji mog膮 pojawi膰 si臋 w sytuacjach takich jak:
*	Obecny spos贸b dzia艂ania, si臋 nie sprawdzi 鈥? b臋dzie skomplikowany i niejasny 
*	Niezb臋dna funkcjonalno艣膰. Zabraknie nam funkcjonalno艣ci z powodu okre艣lonej ju偶 specyfikacji
*	Ewolucja oprogramowania. Poniewa偶 trendy, systemy, api, formaty, wzorce potrafi膮 si臋 zmienia膰, a my w zwi膮zku z tym mo偶emy zastanowi膰 si臋, czy taka zmiana wp艂ywa na nasz projekt.
## Proces 艣ledzenia pracy
*	GitHub jako 藕r贸d艂o informacji o projekcie, post臋pach, dost臋pnych funkcjonalno艣ciach.
*	Praca b臋dzie dzielona na branche, gdzie jeden branch b臋dzie jedn膮 funkcjonalno艣ci膮
*	Main 鈥? obecna stabilna wersja, ga艂膮藕 g艂贸wna projektu
*	Nowe funkcje b臋d膮 wykonywane w branachach, kt贸re po wykonaniu b臋d膮 艂膮czone w odpowiedni branch.
*	Gdy funkcja zostaje uko艅czona zostanie scalona z g艂贸wn膮 ga艂ezi膮
## Wymagania funkcjonalne:
1.	System logowania i rejestracji 
	- [ ]	Utworzenie w艂asnego konta
	- [ ]	Mo偶liwo艣膰 zalogowania si臋 na nasze konto z naszymi informacjami
2.	Ustawienia u偶ytkownika
	- [ ]	U偶ytkownik poprzez wej艣cie w odpowiedni膮 zak艂adk臋 jest w stanie zmieni膰 informacje dotycz膮ce jego konta. Informacje takie jak np. e-mail, nazwa u偶ytkownika czy has艂o.
3.	Zak艂adka z w艂asn膮 biblioteczka
	- [ ]	Dodanie do biblioteczki ksi膮偶ki kt贸r膮 w艂a艣nie czytam/ przeczyta艂em
	- [ ]	Zapisywa膰 swoje w艂asne uwag odno艣nie ksi膮偶ki,
	- [ ]	Zapisanie liczba stron kt贸r膮 przeczyta艂em,
	- [ ]	Mo偶liwo艣膰 okre艣lenia planu czytelniczego,
	- [ ]	Mo偶liwo艣膰 grupowania ksi膮偶ek w nasze w艂asne grupy
	- [ ]	Wystawienie oceny danej pozycji,
	- [ ]	Mo偶liwo艣膰 oznaczeni ksi膮偶ki jako wartej przeczytania.
4.	System umo偶liwiaj膮cy przegl膮d informacji na temat ksi膮偶ek
	- [ ]	Informacje b臋d膮 pobierane z Internetu
	- [ ]	Informacje kt贸re zostan膮 pobrane to np. autor, wydawca, tytu艂, j臋zyk, rok wydania.
	- [ ]	U偶ytkownik otrzyma informacje dotycz膮ce danej frazy wyszukiwania.
	- [ ]	Umieszczanie innych mechanizm贸w
5.	Historia wyszukiwania u偶ytkownika
	- [ ]	Mo偶liwo艣膰 przegl膮du ostatnio wyszukanych pozycji.
6.	System wy艣wietlania informacji o obiektach zwi膮zanych z ksi膮偶kami 
	- [ ]	Pobranie informacji o obiektach w pobli偶u naszej lokalizacji
	- [ ]	Wy艣wietlenie obiekt贸w zwi膮zanych w jaki艣 spos贸b z ksi膮偶kami z naszej okolicy
	- [ ]	Je偶eli mo偶liwe b臋d膮 do pozyskania informacje odno艣nie danych obiekt贸w, tak偶e zostan膮 wy艣wietlone.
7.	Ranking najlepiej ocenianych ksi膮偶ek
	- [ ]	System sprawdza, kt贸re ksi膮偶ki zosta艂y ocenione najwy偶ej przez u偶ytkownik贸w i wy艣wietla je w perspektywie top 100 ksi膮偶ek.
## Wymagania niefunkcjonalne:
1.	Aplikacja b臋dzie podzielona na fronted 鈥? widok i backend - controller
2.	Aplikacja powinna by膰 intuicyjna i prosta w obs艂udze
3.	System logowania powinien odpowiednio walidowa膰 has艂a i konta
4.	System powinien mie膰 dost臋p do bazy danych 
5.	System powinien umo偶liwia膰 nawigowanie po stronie webowej przy pomocy klawiatury
6.	Przetestowanie aplikacji testami jednostkowymi i integracyjnymi
7.	Responsywno艣膰 aplikacji
## Technologie
1.	.NET Core
2.	J臋zyk programowania C#
3.	Relacyjna baza danych SQL z u偶yciem entity frameworka
4.	Sellenium 鈥? testowanie
5.	Docker 鈥? automatyzacja developmentu



