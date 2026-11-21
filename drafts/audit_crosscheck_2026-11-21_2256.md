# GS Quiz — kontrola przekrojowa 2026-11-21, 22:56 Europe/Warsaw

## Zakres i metodologia
Odczytano na nowo `main/questions.json` (blob `a97558c12406e105a4eda1cf9829bc2c316279f2`) oraz `gsquiz-question-drafts/drafts/questions_additions.json` (blob `fa9eef7e28b54d2a9c5c2141f0fc11ed19d20a9c`). Połączono rekordy po ID, zachowując pierwsze wystąpienie. Sprawdzono liczby, pola odpowiedzi, poprawność indeksów, URL i dokładne znormalizowane pytania. Nie jest to pełny audyt faktograficzny ani semantyczny.

## Wyniki
- main: 1595 rekordów; drafts: 1162; suma: 2757; unikatowe ID: **1850**; nakładanie się ID: **907**.
- Region: Polska **479**, Świat **1371**.
- Trudność: Łatwy **351**, Normalny **670**, Trudny **525**, Ekspert **304**.
- Brak poprawnie sformatowanego URL źródła: **688**.
- Dokładne duplikaty treści pytań po normalizacji, z różnymi ID: **0**.
- Koszykówka: **306** unikatowych pytań; pytania zawierające nazwę Turów: **10**; heurystyka NBA: **233** (to nie jest ręcznie potwierdzona liczba).
- Wykryty alarm przy odpowiedziach: `GS-N20261120-22-013`, kategoria wagowa Bartłomieja Bonka. Normalizacja usuwająca znak plus uznaje `105 kg` i `+105 kg` za takie same. **To błąd walidatora, nie dowód błędnych odpowiedzi**; nie poprawiano pytania bez sprawdzenia faktu w źródle.

## Priorytety
1. Ręczna kontrola 688 brakujących URL w main; nie wolno utożsamiać samego istnienia URL z poprawnością źródła.
2. Audyt semantycznych podobieństw, dwuznaczności i poprawnych odpowiedzi, szczególnie w regionie Polska / Łatwy.
3. Weryfikacja NBA i Turowa na podstawie treści, nie samych słów kluczowych.
4. Poprawa normalizatora odpowiedzi: zachowywać semantycznie istotne znaki takie jak `+` w kategoriach wagowych.

## Zmiany
Nowe pytania: **0**. Odrzucone kandydatury: **0**. Zmian w bazie: **0**. Raport zapisany wyłącznie na gałęzi roboczej. `main` i GitHub Pages nietknięte.
