Załączone pliki zawierają nagranie przypadku testowego wykonanego przy pomocy Selenium IDE oraz zrzut ekranu z widocznymi komendami, miejscami gdzie wykonuje sie akcja (obiekt), wartościami nadanymi.

Poniżej opisany przypadek testowy:

PT001

TYTUŁ: Finalizacja zakupu pustego koszyka

OPIS: Sprawdzenie możliwości sfinalizowania zakupu z poziomu pustego koszyka.

WARUNKI WSTĘPNE: uruchomiona aplikacja https://www.saucedemo.com/, zalogowany użytkownik: standard_user

KROKI:

kliknij ikonę koszyka
kliknij przycisk Checkout
wypełnij pole First Name, używając litery A
wypełnij pole Last Name, używając litery B
wypełnij pole Zip/Postal Code, używając litery C
kliknij przycisk Continue
kliknij przycisk Finish
OCZEKIWANY REZULTAT: Brak możliwości przejścia do podsumowania oraz sfinalizowania zakupów z pustym koszykiem. Pojawia się komunikat "Twój koszyk jest pusty".
