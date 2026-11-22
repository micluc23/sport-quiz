# GS Quiz — audyt semantyczny, 2026-11-22 09:55 Europe/Warsaw

## Wejście i zakres
Pobrano aktualne `main/questions.json` (1595 rekordów, blob `a97558c12406e105a4eda1cf9829bc2c316279f2`) i `gsquiz-question-drafts/drafts/questions_additions.json` (1162 rekordy, blob `fa9eef7e28b54d2a9c5c2141f0fc11ed19d20a9c`). Unia po ID: **1850** rekordów (907 wspólnych ID). Nie dodawano nowych pytań. Liczba odrzuconych nowych kandydatur: 0. Poprawki treści: 0.

## Nowe potwierdzone duplikaty semantyczne (2 pary)
1. `SPORT-N20261119-147` i `SPORT-N20261119-CAN-013`: oba pytają o zwycięzcę pierwszego olimpijskiego finału kayak cross mężczyzn w Paryżu 2024. W obu poprawna odpowiedź: **Finn Butcher**. Źródło przypisane obu: https://www.nbcolympics.com/news/olympic-canoeing-paris-2024-fox-sisters-sweep-slalom-carrington-makes-sprint-history . Pierwsze: Świat/Trudny; drugie: Świat/Normalny.
2. `SPORT-N20261119-C011` i `SPORT-N20261119-CYC-004`: oba pytają o brązowego medalistę olimpijskiej jazdy indywidualnej na czas mężczyzn w Paryżu 2024. W obu poprawna odpowiedź: **Wout van Aert**. Źródło przypisane obu: https://www.nbcolympics.com/news/olympic-cycling-paris-2024-biggest-stories-replays-medal-results-and-top-athletes . Oba: Świat/Trudny.

W obu przypadkach zbieżność dotyczy tego samego wydarzenia, miejsca na podium i odpowiedzi, a nie tylko podobnego słownictwa. Zalecenie: przy przyszłym scalaniu zachować po jednym rekordzie z każdej pary. Obecnie nie usuwano rekordów z `main` ani nie zmieniano GitHub Pages.

## Wcześniej wykryta para (ponowne potwierdzenie)
`SPORT-N20261119-C003` i `SPORT-N20261119-CYC-003`: srebrny medal olimpijskiego wyścigu szosowego mężczyzn Paryż 2024 — **Valentin Madouas**. Źródła zapisane: https://www.uci.org/article/olympic-games-paris-2024-evenepoels-extraordinary-double-triumph/7bTX17xnKnj82dlu6ie2lg i https://www.nbcolympics.com/news/olympic-cycling-paris-2024-biggest-stories-replays-medal-results-and-top-athletes .

## Pozostałe ryzyka
- **688** rekordów bez `source`, w tym **58** ze statusem innym niż `do_weryfikacji` (niespójność deklaracji weryfikacji i śladu źródłowego).
- Koszykówka: **306** rekordów; fraza Turów/Zgorzelec występuje w **10**. NBA ~233 to wcześniejsza heurystyka, nie wynik ręcznego potwierdzenia.
- Wyszukiwanie podobieństwa słów zwraca także fałszywe alarmy, np. K-1 vs C-1, złoto vs srebro, 500 m vs 1500 m. Nie należy usuwać automatycznie.
- Adresy URL powyżej są przypisane w bazie; w tym przebiegu nie sprawdzono niezależnie dostępności stron ani faktów w zewnętrznych archiwach. Potwierdzenie duplikatu dotyczy semantycznej tożsamości pytań i zgodności zapisanych odpowiedzi.

## Działania
Nowe: **0**; odrzucone kandydatury: **0**; nowe pary duplikatów: **2**; zmiany pytań: **0**. Tylko dokumentacja na `gsquiz-question-drafts`. Kolejny etap: przegląd pozostałych podobnych par i weryfikacja źródeł pierwotnych przed korektą statusów.
