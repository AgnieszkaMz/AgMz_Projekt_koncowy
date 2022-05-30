Załączony plik zawiera nagranie przypadku testowego wykonanego przy pomocy Selenium IDE.

Poniżej opisany przypadek testowy:

PT001

TYTUŁ: Finalizacja zakupu pustego koszyka

OPIS: Sprawdzenie możliwości sfinalizowania zakupu z poziomu pustego koszyka.

WARUNKI WSTĘPNE: uruchomiona aplikacja https://www.saucedemo.com/, zalogowany użytkownik: standard_user

KROKI:
1. kliknij ikonę koszyka
2. kliknij przycisk Checkout
3. wypełnij pole First Name, używając litery A
4. wypełnij pole Last Name, używając litery B
5. wypełnij pole Zip/Postal Code, używając litery C
6. kliknij przycisk Continue
7. kliknij przycisk Finish

OCZEKIWANY REZULTAT: Brak możliwości przejścia do podsumowania oraz sfinalizowania zakupów z pustym koszykiem. Pojawia się komunikat "Twój koszyk jest pusty".
