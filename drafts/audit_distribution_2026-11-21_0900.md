# GS Quiz — kontrola przekrojowa, 2026-11-21 09:00 Europe/Warsaw

## Zakres
Odczytano aktualne `main/questions.json` (1595 rekordów) i `gsquiz-question-drafts/drafts/questions_additions.json` (1114 rekordów). Analiza unii po ID, bez modyfikowania pytań. To kontrola automatyczna struktury i rozkładu, **nie** pełna weryfikacja faktograficzna ani semantyczna.

## Wyniki
- 2709 rekordów wejściowych; **1802 unikatowe ID**; 907 wystąpień ID ponad pierwsze wystąpienie.
- 0 błędów w liczbie odpowiedzi (wymagane 4), odrębności odpowiedzi i zakresie `correctIndex` (0–3) w zbiorze unikatowym.
- 0 identycznych pytań po normalizacji wielkości liter, akcentów i znaków niealfanumerycznych w zbiorze unikatowym.
- **688 unikatowych rekordów bez prawidłowo rozpoczynającego się `http(s)://` pola `source`**. Nie oznacza to automatycznie błędu odpowiedzi, ale wymaga źródłowej kontroli.
- Regiony: Polska 479 (26,6%), Świat 1323 (73,4%).
- Trudność: Łatwy 330 (18,3%), Normalny 651 (36,1%), Trudny 517 (28,7%), Ekspert 304 (16,9%).
- Koszykówka: **306** unikatowych pytań. Wyszukiwanie szerokim słownikiem NBA i nazw klubów wskazało **225 kandydatów NBA** — to przybliżenie, nie zatwierdzona liczba; 10 pytań zawiera słowa Turów/Zgorzelec. Oba podcele wymagają ręcznego przeglądu treści.
- Dyscypliny z jednym pytaniem: taekwondo, siatkówka plażowa, kolarstwo górskie, kolarstwo BMX, gimnastyka na trampolinie, hokej na trawie, zapasy w stylu wolnym, skoki do wody. Strzelectwo, piłka ręczna i jeździectwo mają po 3 pytania.

## Ryzyka i działania
1. **Priorytet sobotni:** zweryfikowane nowe fakty w słabo obsadzonych dyscyplinach, zwłaszcza Polska/Łatwy; bez przerabiania tego samego faktu na warianty.
2. **Priorytet niedzielny:** ręczny audyt 688 wpisów bez źródeł, zgodności pytań z wiarygodnymi archiwami, wieloznaczności i duplikatów semantycznych.
3. Oddzielić powtórzone ID wynikające z nakładania gałęzi od rzeczywistych konfliktów treści; sam wynik 907 nie dowodzi błędnych rekordów.
4. Znormalizować nazwy dyscyplin tylko po analizie ich semantyki (np. kolarstwo vs kolarstwo BMX), bez automatycznego scalania.

## Wynik tego przebiegu
Nowe pytania: 0. Odrzucone kandydatury: 0 (nie tworzono partii kandydatów). Poprawki w danych: 0. Utworzono wyłącznie niniejszy raport na gałęzi roboczej. Weryfikacja źródeł zewnętrznych nie była częścią tego przekrojowego sprawdzenia.
