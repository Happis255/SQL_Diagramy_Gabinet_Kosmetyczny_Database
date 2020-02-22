# Baza danych aplikacji webowej wspomagającej pracę gabinetu kosmetycznego

System wspomagający pracę gabinetu kosmetycznego składa się z bazy danych odpowiedzialnej za przechowywanie wszystkich niezbędnych danych do funkcjonowania firmy kosmetycznej, na przykład: dane osobowe pracowników, spis raportów i aktualności zamieszczonych w systemie czy spis wszystkich wizyt wykonanych w gabinecie. 

Odpowiedzialna jest również za przechowywanie wszystkich wiadomości i powiadomień generowanych przez system. Ponadto baza danych zawiera również dane niezbędne do funkcjonowania aplikacji klienckiej hostowanej na serwerze webowym, która umożliwia rezerwowanie wizyt przez klientów, przedstawianie zakresu usług gabinetu jak i oferty sprzedażowej czy powiadamianie klienta o nowej promocji.

Na niektórych diagramach została przedstawiowa tylko część funkcjonalnośći z uwagi na ich dużą liczbę.

Wykorzystywane języki:
- Java oraz JavaServer – aplikacja systemu
- MySQL – baza danych
- HTML oraz CSS
- Bootstrap Framework

### Funkcjonalności aplikacji (spełniane przez Bazę Danych)

1) Logowanie i wylogowanie użytkowników – klient / administrator / pracownik.
2) Tworzenie kont pracowników, ich edycja oraz zarządzanie uprawnieniami (systemowymi jaki usługowymi) przez administratora.
3) Dodawanie przez administratora terminu szkoleń i kongresów kosmetycznych, informacji o ich zakresie, wyświetlanie ich w systemie oraz możliwość zapisu przez pracownika.
4) Dodawanie przez administratora bądź zalogowanego w gabinecie pracownika klienta wraz z zamówioną usługą do grafiku (kalendarza), możliwość jego edycji i podglądu.
5) Tworzenie „Kart Informacyjnych” zawierające wskazania i przeciwskazania do zabiegów oraz alergie i nietolerancje organizmu klienta możliwych do edytowania przez klienta oraz „Kart Zabiegowych” informujące o wykonywanych zabiegach u danego klienta.
6) Możliwość prowadzenia książeczki zdrowia pracowników.
7) Dodawanie zatwierdzonych osiągnięć – ukończone szkolenia oraz otrzymane certyfikaty – przez administratora do profilów pracowników oraz ich prezentacja.
8) Dodawanie sprawozdania zawierającego przebieg ostatnio wykonanego przeglądu technicznego (wewnętrzny), serwisowego (zewnętrzny) oraz sporale kontrolne (medyczne), ich daty przeprowadzenia oraz możliwość ustawienia przypomnienia.
9) Możliwość dodawania wybranych sprzętów użytkowych, informacji o nich oraz ich wyświetlanie.
10) Zarządzanie odpadami – utylizacja – generowanie sprawozdania odbioru zarejestrowanych odpadów (data oraz ilość), ustawienie okresowego przypomnienia o zbliżającym się terminie odbioru odpadów oraz generowanie rocznego bilansu utylizacji.
11) Zarządzanie stanem magazynowym materiałów kosmetycznych - możliwość zgłoszenia braków i propozycji zwiększające ofertę o nowości gabinetu przez pracownika oraz stworzenie listy zakupowej przez administratora na ich podstawie.
12) Rejestrowanie wizyt kontrolnych, takich jak sanepid, ZUS czy państwowa inspekcja pracy.
13) Możliwość generowania wykresu zawierającego ilość wykonanych poszczególnych usług w danym miesiącu.
14) Dodawanie przez administratora bądź wyznaczonego pracownika informacji o aktualnych ofertach, pakietach sezonowych, okolicznościowych, świątecznych  i konkursach oraz ich udostępnienie klientowi.
15) Prowadzenie programu motywacyjnego dla pracownika – nadawanie bonusów okolicznościowych i premii.
16) Możliwość prowadzenia spisu wykonanych usług, kto ich wykonał oraz kwota otrzymanej zapłaty.
17) Możliwość podglądu przez pracownika w swoim profilu informacji o wysokości nadchodzącej wypłaty.
18) Ustalanie z miesięcznym wyprzedzeniem grafiku oraz możliwość zgłaszania prośby o jego edycję przez pracownika.
19) Zgłaszanie prośby o przyznanie urlopu bądź poinformowanie o otrzymaniu zwolnienia lekarskiego przez pracownika administratorowi.
20) Możliwość wprowadzenia zakresu zadań gospodarczych poszczególnym pracownikom.
21) Dodawanie w systemie CV potencjalnego pracownika (w przypadku gdy poszukiwany jest pracownik) oraz przesłania go na mail administratora.
22) Możliwość konsultacji online poprzez chat online pomiędzy klientem a pracownikiem.
23) Możliwość przeglądania oferty usług udostępnianych przez gabinet oraz wybór wzorów/kolorów/typu makijażu przez klienta.
24) Możliwość wstępnej rezerwacji terminu wykonania wybranej usługi u wybranego pracownika.
25) Możliwość składania formularza reklamacyjnego.
26) Złożenie zamówienia przez klienta dotyczącego kupna produktu bądź usługi znajdującego się w ofercie gabinetu oraz opłacenia go przelewem bankowym.
27) Usługa lojalnościowa – klient otrzymuje status stałego klienta po skorzystaniu z określonej ilości usług zatwierdzonych przez pracownika. Takiemu klientowi przysługują bonusy określane przez właściciela gabinetu.
28) Automatyczne wysyłanie przypomnienia klientowi o wizycie (mail).
29) Informowanie klienta o procedurze przygotowania się do zabiegu.
30) Informowanie klienta o celu przetwarzania ich danych osobowych (RODO), przez kogo mogą być wyświetlane i kto nimi zarządza.

### Diagramy
###### Diagram DFD kontekstowy
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20DFD%20Kontekstowy.jpg)
###### Diagram DFD systemowy
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20DFD%20Systemowy.png)
###### Diagram ERD przed normalizacją
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20ERD%20Nieznormalizowany.png)
###### Diagram ERD po normalizacji
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20ERD%20Znormalizowany.png)
###### Diagram STD użytkownika niezalogowanego
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20STD%20użytkownika%20niezalogowanego.jpg)
###### Diagram STD użytkownika-administrator
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20STD%20użytkownika-administrator.jpg)
###### Diagram STD użytkownika-pracownik
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20STD%20użytkownika-pracownik.png)
###### Diagram STD użytkownika-klient
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20STD%20użytkownika-klient.jpg)
###### Diagram ELH użytkownik-administrator
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20ELH%20użytkownika-administrator.png)
###### Diagram ELH użytkownik-pracownik
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20ELH%20użytkownika-pracownik.png)
###### Diagram ELH użytkownik-klient
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20ELH%20użytkownika-klient.png)
###### Diagram klas
![Diagramy](https://raw.githubusercontent.com/Happis255/SQL_Gabinet_Kosmetyczny_Database/master/Grafika/Diagram%20Klas.jpg)
