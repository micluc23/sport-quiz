# GS Quiz — audyt integralności, 21.11.2026 20:57 Europe/Warsaw

## Zakres
Pobrano bezpośrednio z GitHub `main/questions.json` (blob `a97558c12406e105a4eda1cf9829bc2c316279f2`) i `gsquiz-question-drafts/drafts/questions_additions.json` (blob `fa9eef7e28b54d2a9c5c2141f0fc11ed19d20a9c`). Deduplikacja po ID w całej unii.

## Wyniki
- Main: 1595; draft: 1162; suma rekordów: 2757; unikatowe ID: **1850**; 907 nakładających się ID, bez rozbieżnej zawartości JSON.
- Brak poprawnie sformatowanego adresu URL źródła: **688** unikatowych pytań. Samo istnienie URL nie potwierdza poprawności źródła.
- Dokładne duplikaty tekstu pytań po normalizacji: **0**.
- Automatyczny walidator zgłosił 1 potencjalny problem z odpowiedziami: `GS-N20261120-22-013`. Odpowiedzi „105 kg” oraz „+105 kg” są **różnymi kategoriami wagowymi**, dlatego wynik jest fałszywym alarmem normalizacji usuwającej znak plus. Nie usuwać ani nie scalać automatycznie; zweryfikować kategorię w oficjalnych wynikach Londynu 2012.
- Rozkład regionów: Polska 479; Świat 1371. Trudności: Łatwy 351, Normalny 670, Trudny 525, Ekspert 304.
- Koszykówka: **306** unikatowych pytań; **10** zawierających „Turów” lub „Zgorzelec”; **234** potencjalne NBA według słownika drużyn i nazwy ligi — to nie jest zweryfikowany wynik semantyczny.
- Najuboższe dyscypliny (po jednym pytaniu): Taekwondo, Siatkówka plażowa, Kolarstwo górskie, Gimnastyka na trampolinie, Hokej na trawie, Zapasy w stylu wolnym, Skoki do wody, Rugby, Kolarstwo torowe, Kajakarstwo górskie.

## Wnioski i decyzje
1. Przed dodawaniem kolejnych pytań rozwiązać problem 688 nieudokumentowanych źródeł oraz ręcznie zweryfikować zgłoszony przypadek kategorii wagowych.
2. Wyszukiwanie duplikatów semantycznych i faktograficzna kontrola 1850 pytań pozostają niezakończone; brak dokładnych duplikatów nie oznacza braku podobnych pytań.
3. Priorytet rozbudowy: Polska / Łatwy i dyscypliny o małej liczebności. Nie dodano pytań bez potwierdzenia źródeł federacyjnych.
4. Nowe pytania: **0**; odrzucone kandydatury: **0**; zmienione istniejące pytania: **0**.
5. Raport ma charakter diagnostyczny, nie jest certyfikatem pełnej poprawności faktów ani dostępności wszystkich URL.

Zmiany wyłącznie w gałęzi `gsquiz-question-drafts`; bez ingerencji w `main` i GitHub Pages.
