# GS Quiz — audyt koncentracji źródeł (2026-11-22, Europe/Warsaw)

## Zakres
Pobrano aktualne `main/questions.json` oraz `gsquiz-question-drafts/drafts/questions_additions.json`. Po deduplikacji według ID: **1850** pytań (1595 w main, 1162 w drafts, 907 wspólnych). Nie dodano pytań ani nie zmieniono treści. Ten przebieg dotyczy **koncentracji adresów źródłowych**, nie potwierdza dostępności HTTP ani poprawności faktów.

## Nowe ustalenia
- 1162 rekordy mają pole source, 688 nie ma go; **tylko 195 różnych adresów URL** obsługuje 1162 pytań.
- Najczęściej powtarzane URL: `https://www.olimpijski.pl/Media/files/edukacja/materialy/90lat_PKOl.pdf` (32 rekordy), NBC Olympics kajakarstwo Paryż 2024 (30), NBC Olympics gimnastyka Paryż 2024 (25), NBA Defensive Player of the Year (25), NBA draft history (25), NBA Most Improved Player (25), NBA champions (23).
- Najliczniejsze domeny: olympics.com (183), nba.com (167), nbcolympics.com (161), olimpijski.pl (85), library.olympics.com (40). Wartości są liczbą przypisań źródła, nie liczbą niezależnych potwierdzeń.
- Kontrola składni URL za pomocą wzorca HTTP(S) nie wykazała podejrzanych formatów w istniejących 1162 polach. **Nie sprawdzono odpowiedzi HTTP ani tego, czy każda strona potwierdza właściwą odpowiedź.**

## Zalecenia audytowe
1. Ręcznie sprawdzić pozycje z najczęściej używanymi źródłami, czy konkretna strona/PDF faktycznie potwierdza *każdy* przypisany fakt, zwłaszcza wieloletnie serie NBA i zestawy medali.
2. Uzupełnić 688 brakujących URL, nie zmieniając statusu na zweryfikowany bez faktycznej kontroli.
3. Rozstrzygnąć wcześniej zgłoszone 14 par semantycznych; nie usuwać rekordów z main w tej gałęzi.
4. Wykonać osobny audyt osiągalności URL i faktograficzny — obecność URL nie jest dowodem weryfikacji.

## Bilans
Nowe pytania: 0; odrzucone kandydatury: 0; poprawki treści: 0; nowe ustalenie: silna koncentracja źródeł. Gałąź docelowa: `gsquiz-question-drafts`; `main` i GitHub Pages bez zmian.
