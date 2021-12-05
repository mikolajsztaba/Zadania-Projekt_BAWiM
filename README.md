# bWAPP - aplikacja do nauki etycznego hackowania
Treści zadań z aplikacji BWAPP
> **Mikołaj Sztaba**, **Kacper Zemła**

-----
# Przygotowanie środowiska do zadań
- Pobranie maszyny wirtualnej bee-box ze strony http://www.itsecgames.com/download.htm
- Wyłączenie trybu offline w Firefoxie już w VM
- Problemy z klawiaturą: system>preferences>keyboard> layouts > add > Usa > Zaznaczamy tą klawiature USA i usuwamy Belgium



-----

# Zadania HTML INJECTION

## Zadanie 1 (metoda GET)
- Poziom low: wprowadź swoje imię i nazwisko 
w dowolnych znacznikach nagłówkach HTML
- Poziom medium: wprowadź adres URL, który będzie
“klikalny” przez użytkownika np.
adres www.google.com

**UWAGA:** polecamy korzystać z: https://www.urlencoder.org/

## Zadanie 2 (metoda POST)
- Poziom medium: stwórz dokładnie taki sam formularz 
za pomocą znaczników HTML,
wykonując je w wybranym przez siebie polu

## Zadanie 3 (blog)
- Stwórz baner informujący użytkownika 
o niezwykłej wygranej wraz 
z przyciskiem do jego odebrania

- Spróbuj wkleić dowolny obrazek
na bloga
-----
# Zadania XSS 

## Zadanie 1
- Wybierz Cross-Site-Scripting Reflected - GET poziom low
- Wyświetl ciasteczka za pomocą alert box przy użyciu skryptu
- Wybierz Cross-Site-Scripting Stored(blog) - poziom low 
- Dodaj wpis do bloga z tym samym skryptem co wcześniej, jeśli zadziała to skopiuj link do strony i spróbuj wkleić ten link w nową kartę i sprawdź czy zadziała

## Zadanie 2
- Wybierz Cross-Site-Scripting Reflected - POST , ale tym razem medium 
- Ponownie wyświetl ciasteczka na stronie. Tym razem tag skrypt jest wyłączony z użycia. Spróbuj użyć atrybutów HTML do wywołania kodu JS.

## Zadanie 3
- Wybierz Cross-Site-Scripting Reflected - GET z poziomem low
- Napisz skrypt, który podmieni atrybut action formularza na stronie. Dzięki temu, gdy ktoś wypełni formularz po wejściu na stronę z Twojego linku dane zostaną przesłane do atakującego.

## Zadanie 4
- Wybierz 	XSS - Stored( Blog ) na poziomie medium. Zablokuj dostęp do bloga dla każdego użytkownika. 
- Podpowiedź: Użyj funkcji alert().
-----
# Zadanie dodatkowe
- Różne poziomy: https://xss-game.appspot.com/
