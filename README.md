# Django_09.02.2025_Dmazur
PROJEKT ZALICZENIOWY_Python Dev_Podstawy budowy aplikacji internetowych Django
"rezerwacja samochodu z wypożyczalni"
(Pycharm - Visual Studio Code) 

Opis
Projekt polega na stworzeniu aplikacji webowej typu full-stack przy użyciu frameworku Django, korzystającej z relacyjnej bazy danych (SQLite lub PostgreSQL). 
Aplikacja umożliwia użytkownikom wyszukiwanie obiektów do rezerwacji, dokonywanie rezerwacji oraz przegladanie historii swoich rezerwacji. 
Wygląd graficzny aplikacji oparty jest na HTML, z użyciem frameworka Bootstrap do zapewnienia responsywnego i atrakcyjnego interfejsu użytkownika.

Technologie
- Django: Framework webowy w języku Python, wykorzystywany do tworzenia aplikacji webowych z użyciem bazy danych.
- SQLite: Relacyjna baza danych używana do przechowywania informacji o obiektach do rezerwacji, rezerwacjach i użytkownikach.
- HTML/CSS: Języki do tworzenia struktury i wyglądu strony internetowej.
- Bootstrap: Framework CSS, który ułatwia tworzenie responsywnych i estetycznych interfejsów użytkownika.
- Python: Język programowania, na którym oparty jest Django.


Skonfigurowanie bazy danych: python manage.py migrate
Uruchomienie serwera: python manage.py runserver
Wejdź na stronę: http://127.0.0.1:8000/

Użycie
- Zarejestruj się lub zaloguj, aby uzyskać dostęp do aplikacji.
- Wybierz auto do rezerwacji z listy dostępnych. 
(filtrowanie po nazwie - sortowanie po brandzie)
- Przeglądaj szczegóły obiektu.
- Przeglądaj swoje historie swoich rezerwacji.
- Dokonaj rezerwacji.
- wróć do strony z wyboream auta lub wyloguj się.
  (trzeba się wylogować inaczej nie można się zalogować jako inny uzytkownik)
TEST(na uzytkowniku):
  login: BabciaJanina
  hasło: Janina1!
  

administrator - zaloguj sie 
  login dominika 
  hasło Axel2025!

- możliowść zarządzania:
  użytkownikami, 
  grupami, 
  samochodami

Zasady zaliczenia
Projekt zostanie oceniony na podstawie:
1. **Zaprezentowania bazy danych** - projektowanie relacyjnej bazy danych (ocena 3.0).
2. **Funkcjonalności podstron** - umożliwienie wyboru obiektu oraz szczegóły rezerwacji (ocena 4.0).
3. **Filtrowanie danych** - dodanie funkcjonalności filtrowania obiektów (ocena 4.5).
4. **Zarządzanie rezerwacjami** - przynajmniej jedna funkcjonalność logowania użytkowników, zarządzanie rezerwacjami przez użytkowników (ocena 5.0).
5. **Bootstrap** - wykorzystanie frameworka Bootstrap do stworzenia responsywnego interfejsu (ocena 5.0).
6. **Deploy aplikacji** - uruchomienie aplikacji na serwerze (ocena 5.0).
