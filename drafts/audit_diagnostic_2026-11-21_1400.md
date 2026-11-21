# GS Quiz — kontrola unii bazy, 2026-11-21 14:00 Europe/Warsaw

## Zakres i metoda
Pobrano aktualne `main/questions.json` (1595 rekordów) i `gsquiz-question-drafts/drafts/questions_additions.json` (1123 rekordy). Złączono po identyfikatorze `id`, zachowując pierwszy rekord (pierwszeństwo `main`). Wynik: **1811 unikatowych ID** z 2718 rekordów; **907 nadmiarowych wystąpień ID**. Liczby dotyczą identyfikatorów, nie potwierdzonej unikatowości semantycznej.

## Wyniki automatycznej kontroli
- 0 błędów schematu: każdy unikatowy rekord ma 4 różne odpowiedzi po normalizacji wielkości liter i odstępów; `correctIndex` jest liczbą całkowitą z zakresu 0–3.
- 688 unikatowych rekordów nie ma pola `source` rozpoczynającego się od `http://` lub `https://`. **Nie oznacza to, że pozostałe adresy zostały sprawdzone jako działające i właściwe.**
- Koszykówka: według poprzedniego raportu 306 rekordów; w tej kontroli 10 pytań o Turów/Zgorzelec (rozpoznanie nazw w pytaniu lub odpowiedziach) i 225 potencjalnych pytań NBA (dopasowanie słownikowe nazw ligi i klubów tylko w treści pytania). **225 nie jest wynikiem audytu semantycznego ani gwarancją 210 pytań stricte NBA.**
- Najmniejsze dyscypliny: Taekwondo, Siatkówka plażowa, Kolarstwo górskie, Gimnastyka na trampolinie, Hokej na trawie, Zapasy w stylu wolnym, Skoki do wody, Rugby (po 1); Strzelectwo, Piłka ręczna, Jeździectwo, Kolarstwo BMX (po 3). Uwaga: rozdrobnione nazwy sportów mogą zniekształcać rozkład.
- Odrębny audyt podobieństwa semantycznego i sprawdzanie faktów w źródłach federacji **nie zostały zakończone**.

## Decyzje
Nowe: **0**; odrzucone nowe kandydatury: **0** (nie przygotowano partii kandydatów). Bez zmian w pytaniach; nie wolno wnioskować z kontroli strukturalnej o poprawności faktograficznej.

## Następne kroki
1. Zidentyfikować i zweryfikować semantycznie 688 rekordów bez źródła, zaczynając od najbardziej ryzykownych dat i rekordów.
2. Sprawdzić NBA i Turów pytanie po pytaniu, bez zawyżania liczników dopasowaniami słownikowymi.
3. Przed każdym dodaniem porównać fakt, odpowiedź i warianty z pełną unią, nie tylko tekst pytania.
4. Nowe pytania dodawać wyłącznie z indywidualnym wiarygodnym URL, po potwierdzeniu odpowiedzi i braku dubla.

Gałąź `main` i GitHub Pages: bez zmian w ramach tego zapisu.
