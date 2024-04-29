# Programowanie Reaktywne - Kolokwium I

Po skopiowaniu projektu na nalezy wykonać trzy zadania:

## Zadanie 1

Do projektu należy dodać 3 pliki: 
- index.html
- script.js
- style.css

Dodaj funkcję w pliku script.js, która będzie obsługiwała dodawanie elementów do listy. Elementy do listy można dodawać za pomocą akcji powiązanej z przyciskiem
Dodaj również funkcję usuwania elementów z listy. Po kliknięciu na dany element, powinien on zostać usunięty z listy.


## Zadanie 2

Do projektu należy dodać dwa pliki:
- navbar.js
- kontakt.html (plik ten musi mieć strukturę strony internetowej - tagi html, head oraz body. Można powielić zawartość pliku index.html)

Zadanie:
- w pliku navbar.js należy zdefiniować zmienną, która będzie zawierać w sobie znacznik html - `<h1>Nawigacja</h1>` oraz dwa znaczniki `a`, 
których atrybuty href będą odpowiedzialne za przeniesienie użytkownika na podstrony `index` oraz `kontakt`. 
Dodatkowo plik ten należy dołączyć do obu podstron projektu.
- pliki `index.html` oraz `kontakt.html` powinny mieć tuż po otwarciu znacznika body umieszczony znacznik `<div class="nav-bar"></div>`. 
Ten pusty znacznik będzie odpowiedzialny za wyświetlenie nawigacji z pliku navbar.js.
- po dołączeniu pliku navbar.js do obu plików html należy umieścić w nich odpowiedni kod, który odniesie się do znacznika
 div i umieści w nim zdefiniowaną w zmiennej nawigację.

## Zadanie 3

Do projektu należy dodać kolejną podstronę (`blog.html`) oraz bibliotekę bootstrap (tylko na tej podstronie).
(dodanie Bilbioteki Bootstrap sprowadza się do dodania stylów: `<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">`)

Za pomocą dodanej biblioteki (jej klas) należy dodać pola:
- tekstowe Email: `<input type="email">`,
- tekstowe Temat: `<input type="text">`,
- textarea Wiadomość: `<textarea></textarea>`,
- przycisk "Wyślij" (class: success),
- przycisk "Wyczyść" (class: danger).

Po wciśnięciu przycisku "Wyślij" - należy sprawdzić, czy wszystkie pola zostały wypełnione. Jeśli walidacja przejdzie poprawnie, to tekst powienien zostać zapisany do pamięci podręcznej przeglądarki (localStorage).
Dodatkowe wymagania: 
- wiadomosc musi mieć na najmniej 5 znaków.

 
Po wybraniu przycisku Wyczyść, fomrmularz zostaje wyczyszczony, a informacja wysłanej wiadomości znika.

Technika rozwiązania dowolna!

https://drive.google.com/drive/folders/11pfjinWe_DXXnDrbn36grhabDhOmotfq?usp=sharing
