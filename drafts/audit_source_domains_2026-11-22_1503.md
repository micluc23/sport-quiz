# GS Quiz — audyt domen źródłowych (22.11.2026, 15:03 Europe/Warsaw)

## Zakres i metodologia
Pobrano ponownie aktualne `main/questions.json` (blob `a97558c12406e105a4eda1cf9829bc2c316279f2`) i `gsquiz-question-drafts/drafts/questions_additions.json` (blob `fa9eef7e28b54d2a9c5c2141f0fc11ed19d20a9c`). Unia po identyfikatorze ID, przy zgodnych rekordach wspólnych: 1595 + 1162 - 907 = **1850**. Audyt automatyczny analizuje domeny i składnię URL, **nie dowodzi dostępności stron ani potwierdzenia faktów**.

## Nowe ustalenia
- 1162 pytań ma URL, 688 nie ma URL.
- URL rozkładają się na **59 różnych hostów** (zapis `www` liczony oddzielnie); jest to inna miara niż 195 unikatowych pełnych adresów w poprzednim raporcie.
- Wszystkie obecne URL mają prefiks HTTP(S) i host w podstawowym sprawdzeniu składni.
- Domena `fitnessvolt.com` występuje przy **15 pytaniach**; jako serwis wtórny wymaga priorytetowego zestawienia z pierwotnymi archiwami federacji. Nie przesądzono o błędności żadnego pytania.
- Brak źródeł z domen Wikipedia, Reddit, YouTube i Google w polu `source`.

## Najczęstsze hosty
- www.olympics.com: 183
- www.nba.com: 167
- www.nbcolympics.com: 161
- olimpijski.pl: 85
- library.olympics.com: 40
- www.olympedia.org: 34
- www.ittf.com: 33
- www.olimpijski.pl: 32
- worldathletics.org: 25
- www.worldarchery.sport: 22
- worldrowing.com: 22
- triathlon.org: 20
- www.olympic.sk: 18
- www.uefa.com: 17
- www.fil-luge.org: 17
- www.fiba.basketball: 15
- fitnessvolt.com: 15
- www.worldaquatics.com: 15
- www.uci.org: 14
- www.bbc.co.uk: 13

## Priorytetowa kolejka do weryfikacji źródeł wtórnych
- `SPORT-N20261119-157`
- `SPORT-N20261119-158`
- `SPORT-N20261119-159`
- `SPORT-N20261119-160`
- `SPORT-N20261119-161`
- `SPORT-N20261119-162`
- `SPORT-N20261119-163`
- `SPORT-N20261119-164`
- `SPORT-N20261119-165`
- `SPORT-N20261119-166`
- `SPORT-N20261119-167`
- `SPORT-N20261119-168`
- `SPORT-N20261119-169`
- `SPORT-N20261119-170`
- `SPORT-N20261119-171`

## Kontrole i ograniczenia
- Kolizje identyfikatorów o różnej treści między plikami: **0**.
- Nowe pytania: **0**; odrzucone kandydatury: **0**; poprawki treści: **0**.
- Nie zmieniono pytań ani gałęzi `main`. Pełne porównanie treści wszystkich 1162 stron ze zdaniami pytań oraz rozstrzygnięcie 14 zgłoszonych par semantycznych pozostają otwarte.
- Podcele koszykówki według wcześniejszych audytów: 306 łącznie, 10 Turów, NBA tylko szacunkowo 232; brak nowej ręcznej klasyfikacji.
