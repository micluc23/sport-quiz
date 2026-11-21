# GS Quiz — kontrola przekrojowa 2026-11-21, ok. 08:00 Europe/Warsaw

Źródła: aktualne `main/questions.json` i `gsquiz-question-drafts/drafts/questions_additions.json`, pobrane przed raportem.

## Wyniki automatycznej kontroli
- Main: 1595 rekordów; drafts: 1114 rekordów; suma: 2709.
- Unikatowe ID w unii: **1802**.
- ID powtarzające się między plikami: **907**. Porównanie pól `question`, `answers`, `correctIndex` nie wykazało konfliktów dla tych ID; są to nakładające się rekordy, nie 907 odrębnych pytań.
- Nieprawidłowa liczba odpowiedzi, powtórzone odpowiedzi lub `correctIndex` poza 0–3: **0**.
- Rekordy bez pola `source`: **688** (wymagają uzupełnienia i weryfikacji, głównie istniejące wpisy).
- Koszykówka: **306** unikatowych ID (poprzedni raport wskazywał 305). Wśród pytań koszykarskich **203** unikatowe ID zawierają w treści dosłownie „NBA” lub „National Basketball Association”; **10** zawiera „Turów”/„Zgorzelec”. To wskaźniki tekstowe, nie pełny audyt semantyczny NBA/Turowa.
- Najmniej liczne dyscypliny po deduplikacji ID: taekwondo, siatkówka plażowa, kolarstwo górskie, BMX, gimnastyka na trampolinie, hokej na trawie, zapasy w stylu wolnym, skoki do wody (po 1); strzelectwo i piłka ręczna (po 3).

## Kandydaci i decyzje
Przeanalizowano 22 kandydatów o polskich medalach olimpijskich. Automatyczny filtr wysokiego podobieństwa odrzucił 15, a 7 pozostałych skierowano do dalszej weryfikacji faktów i semantyki. **Nie dodano żadnego pytania**: część kandydatów była bliska już istniejącym, a przed zapisem brakowało pełnej kontroli źródłowej. W szczególności kandydat o srebrze w Tokio 2020 zawierał mylący rok względem odpowiedzi i nie może być przyjęty.

## Dalsze czynności
1. Zweryfikować wszystkie 688 brakujących źródeł; nie uznawać samych URL za dowód poprawności.
2. Ręcznie przejrzeć podcel NBA: 203 dosłowne wzmianki nie dowodzą ani nie wykluczają ok. 210 pytań tematycznych.
3. Przeprowadzić semantyczną deduplikację po treści i faktach, nie tylko ID; zbadać pytania o tę samą osobę, medal i wydarzenie.
4. Rozwijać najmniejsze kategorie, ze szczególnym uwzględnieniem Polska/Łatwy, dopiero po weryfikacji źródeł federacji/PKOl.

Nie zmieniono `main` ani GitHub Pages. Ten plik dokumentuje diagnozę, nie potwierdza pełnego audytu merytorycznego.
