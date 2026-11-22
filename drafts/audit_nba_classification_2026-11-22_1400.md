# Audyt klasyfikacji NBA — 2026-11-22, 14:00 Europe/Warsaw

## Zakres i metoda
Pobrano na nowo `main/questions.json` (blob `a97558c12406e105a4eda1cf9829bc2c316279f2`, 1595 rekordów) i `gsquiz-question-drafts/drafts/questions_additions.json` (blob `fa9eef7e28b54d2a9c5c2141f0fc11ed19d20a9c`, 1162 rekordów). Złączono po ID, przy pierwszeństwie wersji roboczej. Nie dodawano pytań i nie zmieniano treści.

## Wyniki
- Unikatowe ID w unii: **1850**; koszykówka: **306**.
- Turów Zgorzelec: **10** pytań (identyfikatory: `SPORT-N20261119-TUROW-001`, `SPORT-N20261119-TUROW-002`, `SPORT-N20261119-TUROW-003`, `SPORT-N20261119-TUROW-004`, `SPORT-N20261119-TUROW-005`, `SPORT-N20261119-TUROW-006`, `SPORT-N20261119-TUROW-007`, `SPORT-N20261119-TUROW-008`, `SPORT-N20261119-TUROW-009`, `SPORT-N20261119-TUROW-010`).
- Filtr NBA (nazwy ligi lub klubów): **224** trafień w treści pytania, **8** dodatkowych trafień wyłącznie w wariantach odpowiedzi, razem **232**. To **nie jest liczba ręcznie potwierdzonych pytań NBA**. Samo wystąpienie nazwy zespołu w błędnej odpowiedzi może zawyżać wynik.
- Bez URL źródła: **688**; status `do_weryfikacji`: **630**.
- Nowe pytania: **0**; odrzucone kandydatury: **0**; poprawki danych: **0**.

## Trafienia wyłącznie w odpowiedziach — do klasyfikacji ręcznej
| ID | Pytanie | Poprawna odpowiedź |
|---|---|---|
| `SPORT-0385` | Jak nazywa się liga koszykówki zawodowej w USA i Kanadzie? | NBA |
| `SPORT-N20261120-REC-002` | Przeciwko której drużynie Wilt Chamberlain zdobył 100 punktów 2 marca 1962 roku? | New York Knicks |
| `SPORT-N20261120-REC-006` | Przeciw której drużynie Luka Dončić zdobył 73 punkty w styczniu 2024 roku? | Atlanta Hawks |
| `SPORT-N20261120-REC-017` | Przeciwko jakiej drużynie Scott Skiles ustanowił rekord 30 asyst w grudniu 1990 roku? | Denver Nuggets |
| `SPORT-N20261120-REC-023` | Który zawodnik miał 181 triple-double w karierze, zanim jego rekord pobił Russell Westbrook? | Oscar Robertson |
| `SPORT-N20261120-MIP-012` | W barwach którego klubu Goran Dragić zdobył nagrodę Most Improved Player w sezonie 2013/14? | Phoenix Suns |
| `SPORT-N20261120-MIP-016` | W którym klubie Hedo Türkoğlu grał, gdy zdobył nagrodę Most Improved Player za sezon 2007/08? | Orlando Magic |
| `SPORT-N20261120-ASW-22` | Z jaką drużyną Nate Thurmond zmierzył się podczas swojego pierwszego quadruple-double w 1974 roku? | Atlanta Hawks |

## Ograniczenia i dalsze działania
Wynik filtra jest wskazówką do audytu, nie dowodem przynależności do NBA ani weryfikacją faktów. Przed uznaniem podcelu 210 NBA należy sklasyfikować wszystkie 306 pytań koszykarskich na podstawie sensu pytania, a następnie sprawdzić poprawną odpowiedź w oficjalnych archiwach NBA i FIBA. W tym przebiegu nie potwierdzano indywidualnych faktów ani dostępności stron źródłowych. Nie wykonywano automatycznych korekt bez dowodów. Znane pary duplikatów semantycznych pozostają do rozstrzygnięcia.

## Zmiany
Wyłącznie niniejszy raport w gałęzi `gsquiz-question-drafts`; bez modyfikacji `main` i GitHub Pages.
