# GS Quiz — audyt semantyczny 2026-11-22 02:59 Europe/Warsaw

## Zakres i metoda
Pobrano aktualne `main/questions.json` oraz `gsquiz-question-drafts/drafts/questions_additions.json`. Porównano unię według ID (przy powtórzonym ID priorytet wersji roboczej). Sprawdzono liczbę odpowiedzi, indeks poprawnej odpowiedzi, unikatowość wariantów, znormalizowane identyczne pytania, dostępność pola URL, rozkład regionów i trudności. Dodatkowo porównano pytania w obrębie dyscypliny metodą podobieństwa tokenów (Jaccard); wyniki są kandydatami, nie automatycznymi dowodami duplikacji.

## Wyniki
- main: 1595; drafts: 1162; nakładające się ID: 907; unikatowe ID: **1850**.
- Błędy liczby odpowiedzi / zakresu correctIndex: **0**; identyczne warianty odpowiedzi po normalizacji zachowującej znak plus: **0**.
- Dokładne duplikaty znormalizowanego pytania pod różnymi ID: **0**.
- Brak poprawnie sformatowanego URL źródła: **688**. To kontrola składni/pola, nie sprawdzenie HTTP ani wiarygodności wszystkich odnośników.
- Region: Polska 479, Świat 1371. Trudność: Łatwy 351, Normalny 670, Trudny 525, Ekspert 304.
- Koszykówka: **306**; pytania zawierające Turów/Zgorzelec: **10**; heurystyka słów kluczowych NBA: **233** (niepotwierdzona ręcznie).
- Najmniej reprezentowane: taekwondo, siatkówka plażowa, kolarstwo górskie, gimnastyka na trampolinie, hokej na trawie, zapasy w stylu wolnym, skoki do wody, rugby, kolarstwo torowe i kajakarstwo górskie — po 1.

## Potwierdzony duplikat semantyczny
**SPORT-N20261119-C003**: „Kto wywalczył srebro w olimpijskim wyścigu szosowym mężczyzn w Paryżu 2024?” — odpowiedź Valentin Madouas.

**SPORT-N20261119-CYC-003**: „Kto zdobył srebro w olimpijskim wyścigu szosowym mężczyzn w Paryżu 2024?” — odpowiedź Valentin Madouas.

To **to samo wydarzenie, medal i zawodnik**, mimo zmiany czasownika, kolejności odpowiedzi i poziomu trudności. Oba rekordy są już w `main` (i powtórzone w drafts); nie usunięto ich, ponieważ polecenie zabrania zmian w `main`, a usunięcie wyłącznie z drafts nie usunęłoby duplikatu z unii. Zalecenie: przy przyszłym zatwierdzonym wydaniu usunąć jeden rekord z main; do tego czasu oznaczyć jako problem do rozwiązania, nie liczyć jako dwa unikalne fakty.

Źródła przypisane rekordom:
- https://www.uci.org/article/olympic-games-paris-2024-evenepoels-extraordinary-double-triumph/7bTX17xnKnj82dlu6ie2lg
- https://www.nbcolympics.com/news/olympic-cycling-paris-2024-biggest-stories-replays-medal-results-and-top-athletes

## Kandydaci niebędący duplikatami
- SPORT-N20261119-CAN-020 i SPORT-N20261119-CAN-021: K-1 vs C-1 1000 m — odrębne konkurencje.
- SPORT-0179 i SPORT-0566: pierwszy złoty medal Polski na zimowych IO — pytania o osobę i rok, pokrewny fakt, do decyzji redakcyjnej.
- SPORT-0588 i SPORT-0603: US Open vs Australian Open 2022 — odrębne turnieje.
- Seria SPORT-N20261119-SM-* (Sixth Man of the Year): odrębne sezony, ale monotonia szablonu wymaga oceny redakcyjnej.

## Odrzucone / naprawy
Nowych pytań: **0** (niedzielny zakaz dodawania). Usuniętych pytań: **0**. Potwierdzonych duplikatów semantycznych (par): **1**. Automatyczne usuwanie odrzucono, ponieważ duplikat istnieje w main. W tym przebiegu zapisano tylko dokumentację. Nie wykonano pełnego audytu wszystkich 1850 faktów ani ręcznej kontroli 688 brakujących URL.
