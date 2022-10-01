# Wstęp

Jako warunek konieczny, wymagane jest dodanie do przeglądarki internetowej wtyczki/rozszerzenia ***Tampermonkey*** - menedżera skryptów użytkownika. Oprogramowanie to umożliwia użytkownikowi dodawanie i używanie skryptów użytkownika, będącymi programami JavaScript, które mogą być używane do modyfikowania stron internetowych.

Do pobrania [TUTAJ](https://tampermonkey.net/).

Teoretycznie, działanie skryptów jest takie samo na wszystkich wspieranych przeglądarkach.

## Keyboard Review (skrypt oryginalny)

Jest to skrypt umożliwiający recenzowanie nominacji Wayspot-ów wyłącznie przy pomocy klawiatury, a tym samym ułatwiający i przyspieszający cały proces.

Do pobrania [TUTAJ](https://github.com/tehstone/wayfarer-addons/raw/main/wayfarer-keyboard-review.user.js)

Instrukcja obsługi za [STRONĄ PROJEKTU](https://github.com/tehstone/wayfarer-addons), gdzie znajdują się też inne skrypty dotyczące Wayfarer-a.

- Numbers 1-5 to select a rating for the selected category
- Left & Right arrows to navigate between categories
- Enter key to submit the nomination (will select the Smart Submit option of the Review Timer script is installed).
- Numbers within Rejection Dialog to navigate the reject reason menu
- Backspace within Rejection Dialog to navigate back a level in the reject reason menu
- When the text box in the Rejection Dialog is focused, Shift+Enter will add a newline, Enter will submit the nomination
- Whenever the submit button is active, Ctrl+Enter will select the "Submit and finish reviewing" option
- "D" to mark the selected nomination as a duplicate
- "Q" to open the main photo
- "E" to open the supporting photo
- "R" & "F" to zoom in and out of the map
- If the Location Accuracy rating is focused, "Escape" will exit street view
- Number keys to select Edit options
- Letter keys to select photo options

# BD_wayfarer (W BUDOWIE)

***Do poprawnego działania, skrypt-matka Keyboard Review musi był wyłączony*** 

Wersja skryptu powyżej zmodyfikowana o predefiniowane oceny - wypełnienie formularza recenzji nominacji jednym przyciskiem, zgodnie z tabelą poniżej. Przytrzymanie klawisza ***SHIFT*** spowoduje natychmiastowe wysłanie oceny.

| Klawisz | Ocena ogólna | Nazwa i opis | Znaczenie historyczne | Wyjątkowy wygląd | Bezpieczny dostęp | Lokalizacja |
| :-----: | :----------: | :----------: | :-------------------: | :--------------: | :---------------: | :---------: |
| ***F1***  | ![star] | \-\- | \-\- | \-\- | \-\- | \-\- |
| ***F2***  | ![star]![star] | ![star]![star]![star] | ![star]![star]![star] | ![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star] [^1]<br>![star]![star]![star]![star]![star] [^2] |
| ***F3***  | ![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star] | ![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star] [^1]<br>![star]![star]![star]![star]![star] [^2] |
| ***F4***  | ![star]![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star] | ![star]![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star] [^1]<br>![star]![star]![star]![star]![star] [^2] |
| ***F5***  | ![star]![star]![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star] [^1]<br>![star]![star]![star]![star]![star] [^2] |
| ***F6***  | ![star]![star]![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star]![star]![star] | ![star]![star]![star] [^1]<br>![star]![star]![star]![star]![star] [^2] |

Do pobrania [TUTAJ](https://github.com/bdudek86/wayfarer/raw/main/BD_wayfarer.user.js).

<sup>Rozwijane i testowane na przeglądarce Firefox.<br> Niektóe funkcje działąją poprawnie tylko z polskim interfejsem Street View.<sup>

[star]: star.png
[^1]: Street View niedostępne w proponowanej lokalizacji
[^2]: Street View dostępne w proponowanej lokalizacji
 
