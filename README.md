Program GroobyPortfel.com – program zarządzający finansami.
Ogólny opis:
1.	Program umożliwiający kontrolowanie prywatnych finansów, zarządzanie nimi oraz planowanie .
2.	Program będzie działał w trybie offline, będzie musiał być zainstalowany na urządzeniu użytkownika, a dostęp do niego możliwy tylko po zalogowaniu.  Po uruchomieniu programu wyświetlą się moduły obrazujące stan środków, historię portfela oraz zaplanowane wydatki i dochody
3.	Z programu korzystać będzie każda osoba prywatna chętna do świadomego zarządzania swoimi środkami finansowymi.
4.	Program dostępny w dowolnym momencie, aktualizujący daty oraz dostępne zasoby finansowe po uwzględnieniu ostatnich terminów dochodów/wydatków. 
5.	Celem przedsięwzięcia jest stworzenie łatwego w obsłudze i czytelnego narzędzia do zarządzania budżetami osobistymi tak by uzyskać większą kontrolę finansową.



Specyfikacje procesów 
1. Wprowadzanie danych o dochodach 
2. Umiejscowienie dochodów w czasie
3. Sumowanie dochodów
4. Wprowadzanie danych o wydatkach
5. Sumowanie wydatków
6. Prezentacja salda portfela
7. Prezentacja kalendarza dochodów i wydatków
8. Generowanie przypomnień o nadchodzących terminach







Model przypadków użycia 
Przepływ zdarzeń między aktorem a systemem dla przypadku użycia „Standardowe użycie” w systemie GroobyPortfel.com :
1.	Przypadek użycia rozpoczyna się, gdy klient uruchamia program po naciśnięciu ikony np. na pulpicie. Wyświetla opcja zaloguj lub stwórz nowe konto. Po wybraniu stwórz nowe konto pojawia się formularz do wprowadzenia danych: imię, nazwisko, oraz prośba podanie oraz nazwy użytkownika i hasła. Gdy użytkownik wybierze opcję zaloguj podaje tylko nazwę użytkownika i hasło. 
2.	Po uzupełnieniu danych aktor wybiera opcję dalej i przechodzi do modułu powitalnego nazwanego  gdzie system prosi o podanie ilości posiadanych oszczędności  jak też spodziewanych kwot, terminów wpływów. Następnie prosi o potwierdzenie. ( Jeśli w tym użyciu użytkownik nie zamierza niczego zmieniać naciska pomiń ten krok)
3.	Następnie system poprosi o podanie wszystkich posiadanych zobowiązań jak też spodziewanych wydatków i ich terminów oraz o potwierdzenie. wpływów ( Jeśli w tym użyciu użytkownik nie zamierza niczego zmieniać naciska pomiń ten krok)
4.	System wyświetla poprze analizowaniu danych bilans klienta. 
5.	Klient ma możliwość zmienić widok na : moje oszczędności, moje zobowiązania oraz mój kalendarz.
6.	Po wybraniu opcji mój kalendarz może sprawdzać którego dnia będą wpływy (zaznaczone na zielono) i którego będą wydatki (zaznaczone na czerwono). Po naciśnięciu wybranego dnia pojawi się okno z bardziej szczegółową  informacją.


Przepływ zdarzeń między aktorem a systemem dla przypadku użycia „usuń/aktualizuj dane” w systemie GroobyPortfel.com :
1.	W module powitalnym wybieramy sekcję, w której chcemy edytować lub usunąć dane czyli : moje oszczędności, moje zobowiązania oraz mój kalendarz. 
2.	Po wyświetleniu się danych wybieramy opcję edycji, a następnie wprowadzamy nowe dane.
3.	Jeśli chcemy usunąć dane bez wprowadzania innych naciskamy usuń.
4.	Potem naciskamy powrót do sekcji „ GroobyPortfel ” gdzie wyświetlają się zaktualizowane dane.


SPECYFIKACJA WMAGAŃ BIZNESOWYCH
1.	Wstęp 
2.	Cel
3.	Wymagania funkcjonale:
a)	opisana ogólna wizja systemu, cele jakie ma spełniać oraz kontekst jego powstania
b)	opis użytkowników
c)	opis funkcji systemu
d)	opis formularzy, wyświetlanych danych i operacji na nich wykonywanych
e)	zakres domyślnych raportów, które będą mogły być automatycznie generowane.
f)	diagramy
4.	Wymagania niefunkcjonalne:
a) maksymalna ilości użytkowników, którzy będą mogli w jednym czasie swobodnie korzystać z aplikacji;
b) maksymalnym czasie wdrożenia oraz deadline na uruchomienie
c) wymagania wobec dokumentacji, która ma zostać opracowana przez wykonawcę
d) oczekiwaniach wobec dostawcy, co zadań przez niego wykonywanych po samym wdrożeniu
e) sposób obsługi niedostępności serwera
f) kolorystyka interfejsów (lub zasadach umieszczania logo firmy)


1.	Po zapoznaniu się z rynkiem aplikacji codziennego użytku nasza firm postanowiła wkroczyć w całkiem nowy dla nas gatunek aplikacji.  Po wielu konsultacjach naszej kadry doszliśmy do wniosku, że nasz zespół doskonale odnajdzie się w roli producenta aplikacji dla większej liczby użytkowników. Nasza firma reprezentuje sobą nowoczesne podejście, młody kreatywny zespół oraz odpowiedni budżet na rozwój kadry jaki rozpowszechnianiu wizerunku naszej firmy.
2.	Celem naszego projektu jest zaprojektowanie programu do zarzadzania budżetem użytkownika znanego w późniejszym czasie pod nazwą „GroobyPortfel”. Program oparty jest na darmowej licencji typu Shareware z 3 miesięcznym okresem testowym. Zastosowanie takiej licencji ma na celu zachęcenie jak największej liczby użytkowników oraz sprawdzenie stabilności oraz zainteresowania naszą aplikacją. Nasza firma myśli przyszłościowo, jeżeli nasz program przypadnie do gustu użytkownikom powstanie komercyjna wersja aplikacji przygotowana dla dużych firm z o wiele bardziej rozbudowanym interfejsem. Dlaczego ten plan musi się powieść? Po przenalizowaniu rynku wyciągnęliśmy odpowiednie wnioski. Najważniejszym z nich był brak reklam w aplikacji, które w darmowych programach uniemożliwiały spokojne użytkowanie programu. Uznaliśmy to za warunek konieczny do tego, aby nasza aplikacja miała szanse zaistnieć na rynku. Drugim wnioskiem był przestarzała szata graficzna innych programów odpychająca użytkowników z niższego segmentu wiekowego, który generuje największe wydatki a najmniejsze dochody. W naszej aplikacji wszystko zostało przemyślane, dlatego ostatni dosyć ważny wniosek do jakiego doszliśmy był kompletny brak działań marketingowych producentów takich aplikacji. Nasz zespół marketingowy wynegocjował świetne warunki do zamieszania reklam u twórców popularnych serwisów społecznościowych, czy też medialnych co zapewni nam świetny start w raz z premierą naszej aplikacji.
3.	Wymagania funkcjonalne:
a)	Aplikacja „GroobyPortfel” ma na celu wprowadzenie w życie wielu porad finansowych do zarządzania budżetem, które ułatwią odnalezienie się w coraz trudniejszych realiach życia codziennego. Brak takiej aplikacji opartej na wiedzy ekspertów, może dać odwrotny rezultat jeśli użytkownicy wybiorą niezaufane aplikację, których na rynku pojawia się coraz więcej.
b)	Wszyscy użytkownicy programu posiadają równe uprawnienia. Każdego z nas dotyczy problem braku pieniędzy na określone cele, dlatego nasza aplikacja nie przewiduje podziału na uprawnienia związane z użytkowaniem programu.
c)	Program oferuje przyjazny interfejs, porady ekspertów, zaawansowany system liczenia oraz przewidywania. Dodatkowo program umożliwia zaprogramowanie cyklicznych dochodów lub wydatków na osi czasu, co umożliwia zsynchronizowany z aplikacją kalendarz.
d)	Aplikacja posiada wbudowaną funkcję przechowywania danych jak i również możliwość wyświetlenia wszystkich danych z poziomu panelu użytkownika. Każdy użytkownik po zalogowaniu do programu wypełnia formularz na podstawie, którego system dokonuje obliczeń. Wszystkie obliczenia są wyświetlane po przeanalizowaniu budżetu.
e)	„GroobyPortfel” umożliwia generowanie dokumentów dotyczących naszej sytuacji finansowej. Co pod tym rozumiemy: prognozy dochodów, wydatków jak i również porad.
f)	Diagramy:







4.	Wymagania niefunkcjonalne:	
a)	Aplikacja jest w stanie obsłużyć w danej chwili jednego użytkownika. Natomiast program umożliwia dodawanie kont innych użytkowników komputera.
b)	„GroobyPortfel” ma być gotowe wraz z końcem semestru zimowego.
c)	Program działa w oparciu o język programowania „Java”, można go pobrać z oficjalnej strony naszej firmy. Dla nowych użytkowników przewidziana jest również instrukcja obsługi aplikacji znajdująca się pod tym samym adresem. Natomiast dokładne wymagania sprzętowe zostały zawarte w specyfikacji sprzętowej. 
d)	Nasza firma ma zamiar stworzyć aplikację niezawodną oraz przyjazną dla wszystkich użytkowników. Wraz wprowadzeniem wersji testowej uruchamiamy osobną skrzynkę mailową na którą użytkownicy mogą zgłaszać wszystkie niedogodności związane zdziałaniem aplikacji. Naszym użytkownikom zapewniamy liczne aktualizacje mające na celu uzyskanie jak największego komfortu pracy.
e)	W przypadku problemów z serwerem aplikacja potrafi działać w trybie offline. Pragniemy również poinformować, że w raz z prąca w trybie braku dostępu do sieci internetowej skorzystanie z aktualizacji w danej chwili będzie niemożliwe.
f)	Kolorystyka interfejsów zostanie uzgodniona wraz z wyłonieniem zwycięzcy ankiety zamieszczonej na naszej stronie internetowej, jak i również ankiety mającej charakter wewnętrzny obejmujący cała kadrę pracowników firmy.








Pozostałe diagramy: 

				DIAGRAM KLAS

 







