# Prosty project RestFul API w ASP.NET Core z bazą danych SQL Server

## Opis projektu
Ten projekt to przykładowe RESTful API napisane w technologii ASP.NET Core z wykorzystaniem bazy danych SQL Server. API zawiera zestaw podstawowych operacji CRUD (tworzenie, odczyt, aktualizacja, usuwanie) dla określonych zasobów. 
Projekt ten może być używany jako punkt wyjścia do tworzenia bardziej zaawansowanych interfejsów API lub jako baza do nauki dla osób chcących zacząć pracę z technologią ASP.NET Core i bazami danych SQL Server.

## Wymagania wstępne
1. **ASP.NET Core SDK**: Aby uruchomić ten projekt, musisz zainstalować SDK ASP.NET Core. Możesz pobrać i zainstalować je z oficjalnej strony Microsoft lub użyć menedżera pakietów dla swojego systemu operacyjnego.
2. **SQL Server**: Projekt korzysta z bazy danych SQL Server, więc upewnij się, że masz dostęp do serwera SQL Server i utworzoną bazę danych.

## Konfiguracja
1. **Baza danych**: Zaktualizuj ustawienia połączenia do bazy danych w pliku `appsettings.json` w sekcji `ConnectionStrings`.
2. **Migracje**: Wykonaj migracje, aby utworzyć schemat bazy danych. Otwórz NuGet Package Manager Console w Visual Studio, a następnie wykonaj poniższe polecenia:
   ```
   Update-Database
   
   ```
3. **Uruchomienie**: Uruchom projekt za pomocą komendy `dotnet run` lub użyj środowiska IDE, takiego jak Visual Studio, do uruchomienia aplikacji.

## Dokumentacja API
Po uruchomieniu projektu możesz przeglądać dokumentację API, odwiedzając ścieżkę `/swagger` w twojej przeglądarce. Znajdziesz tam szczegółowe informacje na temat wszystkich dostępnych endpointów, ich parametrów oraz sposobu użycia.


