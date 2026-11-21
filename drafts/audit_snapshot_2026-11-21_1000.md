# GS Quiz — kontrola unii bazy, 2026-11-21 10:00 Europe/Warsaw

## Zakres i metoda
Odczytano aktualne `main/questions.json` (blob `a97558c12406e105a4eda1cf9829bc2c316279f2`) oraz `gsquiz-question-drafts/drafts/questions_additions.json` (blob `0d4713cb2042bfbb1b7f1f41c7eec10b6308c898`). Deduplikacja według `id`, porównanie pełnych rekordów dla powtórzonych ID, sprawdzenie czterech unikalnych odpowiedzi, indeksu 0–3, URL źródła, normalizacja tekstu pytań (małe litery, usunięcie znaków diakrytycznych i interpunkcji) dla dokładnych dubli.

## Wyniki
- Main: **1595**; drafts: **1114**; razem: **2709** rekordów.
- Unikatowe ID: **1802**; powtórzone ID między plikami: **907**, bez rozbieżności całych rekordów.
- Niepoprawne zestawy odpowiedzi / indeksy: **0**.
- Brak poprawnego URL źródła: **688** unikatowych rekordów. Wymagają osobnej weryfikacji; nie są automatycznie błędne.
- Identyczne pytania po normalizacji tekstu wśród unikatowych ID: **0**. Nie jest to audyt dubli semantycznych.
- Region: Polska **479**, Świat **1323**.
- Trudność: Łatwy **330**, Normalny **651**, Trudny **517**, Ekspert **304**.
- Koszykówka: **306**; Turów/Zgorzelec wymieniony w treści lub odpowiedziach **10** (ID `SPORT-N20261119-TUROW-001` do `010`); szeroki filtr NBA (NBA lub nazwy klubów w pytaniu/odpowiedziach) wskazuje **234 kandydatów**, nie zaś 234 potwierdzone pytania o NBA. Wymaga ręcznej klasyfikacji i weryfikacji faktów.
- Najuboższe dyscypliny (po 1): Taekwondo, Siatkówka plażowa, Kolarstwo górskie, Kolarstwo BMX, Gimnastyka na trampolinie, Hokej na trawie, Zapasy w stylu wolnym, Skoki do wody. Po 3: Strzelectwo, Piłka ręczna, Jeździectwo.

## Wnioski i dalsze kroki
Priorytet sobotniej rozbudowy: niedoreprezentowane dyscypliny, szczególnie region Polska i poziom Łatwy; każdą propozycję sprawdzać w źródle federacji lub oficjalnym archiwum i porównywać znaczeniowo z pełną unią. Nie dodano nowych pytań w tej kontroli: **0 dodanych, 0 odrzuconych kandydatów**. W niedzielę: przegląd 688 brakujących URL, semantycznych podobieństw, jednoznaczności pytań, zgodności `correctIndex` z faktami, oraz 234 kandydatów NBA. Wyniki automatyczne nie stanowią certyfikatu merytorycznej poprawności całej bazy.

## Zasady zmian
Raport na gałęzi roboczej, bez zmian w `main` i GitHub Pages.
