# GS Quiz — audyt źródeł i nakładania gałęzi, 2026-11-22 04:58 Europe/Warsaw

## Zakres
Odczytano aktualne `main/questions.json` (blob `a97558c12406e105a4eda1cf9829bc2c316279f2`) i `gsquiz-question-drafts/drafts/questions_additions.json` (blob `fa9eef7e28b54d2a9c5c2141f0fc11ed19d20a9c`). Kontrola dotyczy struktury i metadanych; **nie jest** potwierdzeniem faktograficznym każdego pytania ani dostępności stron źródłowych.

## Wyniki
- Main: 1595; draft: 1162; wspólne ID: 907; unia po ID: **1850**.
- Wszystkie 907 wspólnych rekordów ma **identyczną serializację JSON** w obu plikach. Nie stwierdzono konfliktów pól pytania, odpowiedzi, poprawnego indeksu, regionu, dyscypliny ani trudności.
- 688 rekordów bez URL źródła: **wszystkie 688 w main; zero w draft**. To wskazuje, że braków nie da się usunąć wyłącznie uzupełnieniem obecnych 1162 rekordów roboczych bez dopisania metadanych/override dla pozostałych rekordów main lub późniejszego kontrolowanego scalenia. Nie dopisywano fikcyjnych źródeł.
- 0 błędów struktury czterech różnych odpowiedzi i zakresu `correctIndex`; 0 dokładnych duplikatów pytań po normalizacji znaków.
- Region: Polska 479, Świat 1371. Trudność: Łatwy 351, Normalny 670, Trudny 525, Ekspert 304. Polska/Łatwy: 132.
- Koszykówka: 306; pytania z frazą Turów: 10; automatyczny filtr nazw i terminów NBA: 233 — **wynik orientacyjny, nie ręcznie zweryfikowana liczba NBA**.
- Najuboższe dyscypliny (po 1): taekwondo, siatkówka plażowa, kolarstwo górskie, gimnastyka na trampolinie, hokej na trawie, zapasy w stylu wolnym, skoki do wody, rugby, kolarstwo torowe, kajakarstwo górskie.

## Ustalenia i zalecenia
1. Priorytetem jest źródłowa weryfikacja 688 rekordów z main. Brak URL nie dowodzi błędnego faktu; oznacza brak ścieżki audytowej.
2. Wcześniej zgłoszona para semantyczna `SPORT-N20261119-C003` / `SPORT-N20261119-CYC-003` wymaga rozwiązania na etapie scalania, ponieważ obie pozycje są już w main; nie usuwano ich w tej gałęzi.
3. Przy audycie odpowiedzi wagowych nie normalizować `105 kg` i `+105 kg` do jednej wartości.
4. Ręcznie skontrolować kandydatów NBA i 10 pozycji o Turowie; sam filtr słów kluczowych nie stanowi weryfikacji.
5. Nie modyfikować main ani GitHub Pages. Przed wdrożeniem napraw ustalić strategię override dla rekordów występujących wyłącznie w main.

## Operacje
Nowe pytania: 0. Odrzucone kandydatury: 0. Poprawki pytań: 0. Zmiany wyłącznie w niniejszej dokumentacji na gałęzi roboczej. Brak nowych zewnętrznych źródeł faktograficznych w tym przebiegu.
