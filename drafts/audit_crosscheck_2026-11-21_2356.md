# GS Quiz — kontrola przekrojowa 2026-11-21 23:56 Europe/Warsaw

## Zakres
Odczytano bieżące `main/questions.json` (1595 rekordów, blob `a97558c12406e105a4eda1cf9829bc2c316279f2`) oraz `gsquiz-question-drafts/drafts/questions_additions.json` (1162 rekordy, blob `fa9eef7e28b54d2a9c5c2141f0fc11ed19d20a9c`). Połączenie po ID: **1850 unikatowych rekordów**, 907 nakładających się ID, bez konfliktów treści po pominięciu pól source/status.

## Kontrola automatyczna
- 0 błędów: liczba odpowiedzi inna niż 4, identyczne odpowiedzi (po obcięciu białych znaków i zmianie wielkości liter), correctIndex poza 0–3.
- 0 dokładnych duplikatów znormalizowanej treści pytania pomiędzy różnymi ID.
- **688 pytań bez poprawnie sformatowanego URL source** (pierwsze: SPORT-0001 do SPORT-0008). Samo istnienie URL nie dowodzi poprawności ani dostępności źródła.
- **306 pytań z kategorią Koszykówka**, 10 z odniesieniem do Turów/Zgorzelec; heurystyka słów NBA i wybranych klubów wykrywa 220, co NIE jest ręcznym potwierdzeniem docelowych ~210 NBA.

## Najuboższe kombinacje (po 1 pytaniu)
Świat/Łatwy/Kolarstwo; Świat/Ekspert/Szermierka; Polska/Trudny/Szermierka; Polska/Normalny/Wspinaczka sportowa; Świat/Łatwy/Kajakarstwo; Polska/Ekspert/Skoki narciarskie; Polska/Normalny/Saneczkarstwo; Polska/Ekspert/Saneczkarstwo; Polska/Trudny/Wspinaczka sportowa; Polska/Ekspert/Kolarstwo; Świat/Ekspert/Zapasy; Świat/Łatwy/Judo; Świat/Łatwy/Skoki narciarskie; Polska/Łatwy/Strzelectwo; Polska/Trudny/Podnoszenie ciężarów.

## Granice ustaleń i kolejny audyt
Nie wykonano pełnego sprawdzenia faktów, poprawności źródeł HTTP ani semantycznego porównania wszystkich pytań; brak duplikatów dosłownych nie wyklucza parafraz. Weryfikować ręcznie brakujące URL, różnice w kategoriach historycznych (np. 105 kg vs +105 kg), podobne fakty i prawidłowość odpowiedzi. Brak zatwierdzonych nowych pytań i brak odrzuconych kandydatur w tym przebiegu. Nie zmieniano bazy pytań ani gałęzi main. Raport jest dokumentacją diagnostyczną, nie certyfikatem faktograficznym.
