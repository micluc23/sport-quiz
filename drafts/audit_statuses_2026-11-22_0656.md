# GS Quiz — audyt statusów i źródeł (2026-11-22, 06:56 Europe/Warsaw)

## Zakres i metoda
Pobrano aktualne `main/questions.json` (1595 rekordów; blob a97558c12406e105a4eda1cf9829bc2c316279f2) oraz `gsquiz-question-drafts/drafts/questions_additions.json` (1162 rekordów; blob fa9eef7e28b54d2a9c5c2141f0fc11ed19d20a9c). Po złączeniu według ID: **1850 unikatowych ID**; nakładanie 907. Nie dodawano pytań.

## Nowe ustalenie: status weryfikacji
- **630 rekordów** ma status `do_weryfikacji`, zatem nie można nazywać całej bazy faktograficznie zatwierdzoną.
- **688 rekordów** nie ma pola `source` z adresem URL. Weryfikacja poprawności odpowiedzi wymaga uzupełnienia źródeł i kontroli dokumentów źródłowych.
- Statusy weryfikacji: `do_weryfikacji`: 630; `zweryfikowano_zrodlo_2026-11-19`: 539; `zweryfikowano_zrodlo_2026-11-18`: 9; `zweryfikowano_zrodlo_2026-11-20`: 485; `zweryfikowano_zrodlo_2026-11-21`: 187.
- Status oznaczony jako `zweryfikowano_zrodlo_...` nie jest dowodem, że URL nadal działa lub że potwierdza dokładnie zadane pytanie.

## Kontrola struktury
- Nieprawidłowe układy 4 odpowiedzi / powtarzające się odpowiedzi po normalizacji / `correctIndex` poza 0–3: **0**.
- Dokładne duplikaty treści pytania po normalizacji: **0**. Kontrola ta nie wykrywa parafraz; wcześniejszy raport wskazał semantyczny duplikat dotyczący Valentina Madouasa.
- Koszykówka: **306**; Turów Zgorzelec: **10**. Podcel NBA: **niepotwierdzony ręcznie**, nie należy traktować automatycznych filtrów jako dokładnego wyniku.

## Priorytet dalszej kontroli
Najpierw 630 rekordów z `do_weryfikacji` i 688 bez źródła, następnie ręczny przegląd parafraz i rozstrzygnięcie duplikatu Madouasa. Wszelkie poprawki wyłącznie na gałęzi roboczej, bez modyfikacji `main`.

## Bilans
Nowe 0; odrzucone 0; zmienione pytania 0; dokumentacja audytu 1. Kontrola źródeł w tym przebiegu obejmowała obecność pola, nie dostępność ani potwierdzenie faktów w źródłach.
