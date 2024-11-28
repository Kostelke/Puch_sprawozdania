Ćwiczenie: Baza danych MS SQL Server w Azure
link - https://github.com/Kostelke/Puch_sprawozdania/blob/main/Lab_1/lab_1_sprawozdanie.md

Krok 1: Utworzenie konta w Azure
Rejestracja na stronie Azure przebiegła bez przeszkód
Krok 2: Utworzenie instancji Azure SQL Database
Baza została stowrzona korzystając z domyślnych ustawień
![zdjecie 2](2.png)

c. Wybór źródła danych
Jako źródło danych wybrałem microsoftową bazę adventure Works
d. Konfiguracja serwera
Stworzyłem nowy serwer Puch-server
e. Wybór opcji cenowych i rozmiaru
Wybrałem opcję domyślne ( najtańsze/ zawierajace sie w darmowym pakiecie)
f. Dodatkowe ustawienia
Ustawienia te były włączone domyślnie
![zdjecie 1](1.png)

Krok 3: Zatwierdzenie i wdrożenie
![Zdjecie 3](3.png)

Krok 4: Połączenie z bazą danych
Poniewa pracuje na MAC-OS musiałem uzyc w tym celu DBeavera
![Zdjecie 4](4.png)

Krok 5: Tworzenie aplikacji
Po zainstalowaniu pakietów napisałem prosty kod pobierajacy
![zdjecie 5](5.png)

Krok 6: Konfiguracja maszyny wirtualnej
Niestey w tym korku napotkalem problem - pomimo stworzenia maszyny wirutalnej, nie mogłem sie potem z nią połączyc
przez remote desktop, nie działała take konsola - ustawiłem porty itp, w remoteDesktop widziałem po prostu czarny ekran
![Zdjecie 6](6.png)

Krok 7: Praca z Azure Table Storage
Stowrzyłem odpowiedni zasób
![Zdjecie 8](8.png)

po zainstalowaniu odpowiednich pakietów napisałem prosty kod realizujacy funkcjonalność CRUD
![Zdjecie 12](12.png)

1. Konfiguracja Firewalla Azure SQL Database
   Juz przy początku tworzenia SQL Dtabase ustawiłem te wartości tak by akcpetowały tylko moje IP.
   Azure Cosmos DB
   Stowrzyłem Azure DB z SQL Api
   ![zdjecie 13](13.png)

Nastepnie stworzyłem baze danych i kontener
![Zdjecie 14](14.png)

Oraz dodałem testowo jeden plik JSON
![zdjecie 15](15.png)

Integracja z aplikacją:

Napisałem prostą aplikację (CosmosCbService i program ) do realizacji obłsugi CRUD
![Zdjecie 16](16.png)
