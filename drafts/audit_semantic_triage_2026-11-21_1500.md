# GS Quiz — audyt integralności i triage podobieństw (2026-11-21 15:00 CET)

## Zakres
Porównano aktualne `main/questions.json` (1595 rekordów) i `gsquiz-question-drafts/drafts/questions_additions.json` (1123 rekordy). Unia po `id`: **1811** rekordów. 907 ID występuje w obu plikach; wszystkie 907 nakładających się obiektów mają identyczną pełną treść JSON. Nie traktować tych kopii jako 907 różnych pytań.

## Wyniki kontroli
- 688 z 1811 unikatowych pytań bez poprawnego URL `source`; wszystkie 688 pochodzą z `main`. Plik roboczy ma 0 brakujących URL. Brak URL nie dowodzi fałszywości pytania, ale blokuje pełny audyt źródłowy.
- 0 pytań o niepoprawnej strukturze czterech odpowiedzi, zduplikowanych odpowiedziach lub `correctIndex` poza zakresem 0–3.
- 0 dokładnych duplikatów znormalizowanej treści pytań wśród 1811 unikatowych ID.
- 530 **par kandydackich** o wysokim podobieństwie tokenowym (>=0,83 wspólnych słów o długości >3, w ramach jednej dyscypliny). To **nie jest** liczba potwierdzonych duplikatów semantycznych; różnice w latach, konkurencjach i medalach mogą oznaczać niezależne fakty.

## Przykłady do ręcznej decyzji (nie usuwać automatycznie)
1. `SPORT-N20261119-CAN-020` i `SPORT-N20261119-CAN-021`: kajakarstwo Paryż 2024, K-1 1000 m kontra C-1 1000 m — różne konkurencje, mimo podobnego brzmienia.
2. `SPORT-N20261120-R11-009` i `SPORT-N20261120-R11-010`: minimalny wiek w triathlonie standardowym kontra sprint; sprawdzić źródłowe przepisy World Triathlon 2025.
3. `SPORT-N20261119-SSK-002` i `SPORT-N20261119-SSK-008`: srebro w Pekinie 2022 na 500 m kontra 1500 m.
4. `SPORT-0124` i `SPORT-0513`: trener reprezentacji siatkarskiej w 2014 kontra 2018 — różne edycje MŚ.
5. `SPORT-N20261119-GYM-009` i `SPORT-N20261119-GYM-010`: srebro kontra brąz w tej samej konkurencji — odrębne wyniki, lecz potencjalna monotonia rozgrywki.

## Koszykówka
W unii: wcześniej raportowane 306 pytań; 10 pytań z dosłowną wzmianką o Turowie/Zgorzelcu. Wyszukiwanie NBA po nazwie ligi i wybranych klubach: 224 kandydatów, nie pełna klasyfikacja tematyczna. **Nie oznaczać celu ~210 NBA jako ręcznie zweryfikowanego.**

## Zalecenia
1. W niedzielę przejść od diagnozy do ręcznej kontroli faktów, źródeł i 530 par kandydackich; oznaczać osobno: rzeczywisty duplikat / odrębny fakt / monotonia.
2. Najpierw uzupełniać 688 brakujących źródeł z wiarygodnych federacji i archiwów; bez weryfikacji nie przypisywać losowych URL.
3. Przy rozbudowie preferować Polska/Łatwy i ubogie kombinacje; nie tworzyć seryjnych pytań zmieniających tylko rok, medal lub dystans.
4. Dokumentować każde odrzucenie z ID, powodem i odniesieniem do istniejącego pytania.

## Zmiany w tym przebiegu
Nowe pytania: **0**. Odrzucone nowe kandydatury: **0**. Zmieniono wyłącznie dokumentację na gałęzi roboczej. Nie wykonano pełnego ręcznego audytu faktograficznego; nie przypisywać mu takiego statusu.
