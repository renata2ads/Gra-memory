# Wymagania – gra Memory

## Cel
- Projekt do portfolio, który pokazuje czysty kod, dynamiczne UI i logiczne myślenie.
- Odbiorcy: dorośli.
- Gotowe, gdy gra jest w pełni grywalna, bez błędów blokowania kart, i zapisuje najlepsze wyniki.

## Technologia
- JavaScript bez frameworków i narzędzi do budowania. Gra uruchamia się przez `index.html`.
- Komputer (PC), sterowanie myszą.
- Kod podzielony na moduły: logika gry osobno od UI.
- Testy automatyczne logiki gry.

## Zasady gry
- Plansza 6×6: 36 kart, 18 par emoji.
- Gra startuje bez podglądu kart.
- Niepasująca para jest widoczna przez 1 sekundę. W tym czasie klikanie jest zablokowane, potem karty zakrywają się z animacją.
- Gra kończy się po odkryciu wszystkich par.
- Tryb dla jednego gracza.

## Punktacja i ranking
- Liczba ruchów (1 ruch = odkrycie pary kart) i czas gry (stoper).
- Ranking top 10 w LocalStorage: ruchy, czas, data.
- Kolejność: mniej ruchów, przy remisie krótszy czas.

## Interfejs
- Tytuł gry: „Neon Memory” – widoczny na ekranie startowym i w tytule karty przeglądarki.
- Ekran startowy: przycisk „Graj” i ranking.
- Ekran gry: plansza, licznik ruchów, stoper.
- Ekran końca gry: wynik i gratulacje.
- Ciemny motyw, karty w neonowych kolorach, wysoki kontrast.
- Obracanie kart w 3D.
- Dźwięki kliknięcia, trafienia i pomyłki.
- Język polski.

## Poza zakresem
- Logowanie użytkowników.
- Muzyka w tle.
- Wybór poziomu trudności.
- Zapis i wznawianie przerwanej gry.
- Gra z komputerem (AI) – kolejny etap.
