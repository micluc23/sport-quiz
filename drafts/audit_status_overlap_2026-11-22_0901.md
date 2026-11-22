# GS Quiz — audyt 2026-11-22, 09:01 Europe/Warsaw

## Zakres i metoda
Pobrano na nowo `main/questions.json` (1595 rekordów) oraz `gsquiz-question-drafts/drafts/questions_additions.json` (1162 rekordy). Po unii po ID: **1850** rekordów; 907 ID wspólnych. Audyt automatyczny dotyczył struktury odpowiedzi, obecności źródeł, statusów, kategorii i wybranych podobieństw semantycznych. Nie oznacza pełnej weryfikacji faktograficznej.

## Nowe ustalenie: zaległości weryfikacyjne
- **630** rekordów ma status `do_weryfikacji`.
- **688** rekordów nie ma pola `source` z URL.
- **Wszystkie 630** rekordów o statusie `do_weryfikacji` należy do grupy 688 bez URL. Pozostałe **58** bez URL mają inny status; ich status nie stanowi wystarczającego dowodu weryfikacji źródłowej.
- 0 błędów struktury (4 odpowiedzi, `correctIndex` od 0 do 3); 0 przypadków powtórzenia odpowiedzi po normalizacji; 0 dokładnych duplikatów znormalizowanej treści o różnych ID.
- Nie sprawdzono działania wszystkich zewnętrznych linków ani zgodności wszystkich faktów z archiwami.

## Koszykówka i kategorie
306 rekordów z `sport=Koszykówka`; 10 z odniesieniem do Turowa/Zgorzelca. NBA: klasyfikacja słowami kluczowymi nie daje wiarygodnego potwierdzenia podcelu 210; wymagany ręczny przegląd. Przykładowe ubogie kombinacje: Polska/Łatwy/Strzelectwo = 1; Polska/Łatwy/Piłka ręczna = 1; Polska/Trudny/Szermierka = 1.

## Duplikat semantyczny — do decyzji
`SPORT-N20261119-C003` oraz `SPORT-N20261119-CYC-003` pytają o tego samego srebrnego medalistę olimpijskiego wyścigu szosowego mężczyzn Paryż 2024 (Valentin Madouas). To ten sam fakt przy odmiennym sformułowaniu. Oba rekordy znajdują się w main; nie modyfikowano main. Źródła w rekordach: https://www.uci.org/article/olympic-games-paris-2024-evenepoels-extraordinary-double-triumph/7bTX17xnKnj82dlu6ie2lg i https://www.nbcolympics.com/news/olympic-cycling-paris-2024-biggest-stories-replays-medal-results-and-top-athletes. Nie przeprowadzono w tej sesji niezależnego sprawdzenia dostępności tych stron.

## Zmiany i odrzucenia
Nowe: **0**; odrzucone kandydatury: **0**; poprawki treści: **0**. Zapisano wyłącznie ten raport na gałęzi roboczej. Priorytet dalszego audytu: 58 rekordów bez URL mimo statusu innego niż `do_weryfikacji`, następnie 630 oczekujących, ręczne sprawdzenie źródeł i par semantycznych.
