# Audyt spójności statusów i źródeł — 2026-11-22 16:58 Europe/Warsaw

## Metoda
Pobrano aktualne `main/questions.json` i `gsquiz-question-drafts/drafts/questions_additions.json`; połączono po ID (rekord gałęzi roboczej ma pierwszeństwo). To kontrola metadanych, nie dowód merytorycznej poprawności pytań ani dostępności adresów.

- main: 1595; drafts: 1162; wspólne ID: 907; unikatowe: 1850.
- Bez poprawnego URL źródła: 688.
- Status inny niż `do_weryfikacji`, ale bez URL: **58**.
- Nowe pytania: 0; odrzucone: 0; poprawki rekordów: 0.
- Rozkład 58 przypadków: Koszykówka: 17; Piłka nożna: 7; Siatkówka: 10; Sporty zimowe: 11; Sporty motorowe: 4; Lekkoatletyka: 7; Tenis: 1; Ogólne: 1.

## Rekordy do rozstrzygnięcia
Poniższy status `zweryfikowano_zrodlo_*` nie ma udokumentowanego URL w rekordzie. Nie należy automatycznie dopisywać źródeł ani usuwać statusu bez sprawdzenia historii i źródeł pierwotnych.

- `SPORT-0002` — Koszykówka / Polska / Łatwy: Ilu zawodników jednej drużyny przebywa na boisku podczas meczu koszykówki?
- `SPORT-0006` — Koszykówka / Polska / Łatwy: Ile punktów daje celny rzut wolny w koszykówce?
- `SPORT-0010` — Koszykówka / Polska / Łatwy: Ile punktów daje celny rzut zza linii trzech punktów?
- `SPORT-0014` — Koszykówka / Świat / Łatwy: Ile kwart ma standardowy mecz koszykówki?
- `SPORT-0022` — Piłka nożna / Świat / Łatwy: Który kraj wygrał piłkarski mundial w 2022 roku?
- `SPORT-0028` — Siatkówka / Polska / Łatwy: Ile punktów zwykle trzeba zdobyć, aby wygrać set siatkówki halowej (nie tie-break), z przewagą dwóch?
- `SPORT-0029` — Siatkówka / Świat / Łatwy: Ile setów musi wygrać drużyna, aby wygrać mecz siatkówki halowej?
- `SPORT-0030` — Siatkówka / Świat / Łatwy: Jak nazywa się zawodnik w siatkówce specjalizujący się w obronie i przyjęciu, noszący inny kolor koszulki?
- `SPORT-0031` — Siatkówka / Świat / Łatwy: Czy w siatkówce halowej wolno odbić piłkę nogą?
- `SPORT-0032` — Siatkówka / Świat / Łatwy: Ile maksymalnie odbić może wykonać drużyna przed przebiciem piłki na drugą stronę (bez liczenia bloku)?
- `SPORT-0041` — Koszykówka / Polska / Normalny: Które miejsce zajęła Polska na mistrzostwach świata koszykarzy w 2019 roku?
- `SPORT-0043` — Piłka nożna / Polska / Normalny: Kto strzelił zwycięskiego gola dla Polski w meczu z Portugalią na MŚ 1986?
- `SPORT-0053` — Piłka nożna / Świat / Normalny: Która reprezentacja wygrała mistrzostwa świata w 2010 roku?
- `SPORT-0055` — Siatkówka / Świat / Normalny: Do ilu punktów rozgrywa się tie-break w siatkówce halowej (z przewagą dwóch)?
- `SPORT-0056` — Siatkówka / Świat / Normalny: Ile punktów daje wygrana akcja w siatkówce halowej?
- `SPORT-0063` — Koszykówka / Polska / Trudny: W jakim mieście rozegrano finał mistrzostw Europy koszykarzy w 1963 roku?
- `SPORT-0066` — Siatkówka / Polska / Trudny: Który polski klub siatkarski wygrał Ligę Mistrzów CEV w 2021 roku?
- `SPORT-0071` — Piłka nożna / Świat / Trudny: Która reprezentacja wygrała pierwsze mistrzostwa świata FIFA w 1930 roku?
- `SPORT-0074` — Koszykówka / Świat / Trudny: Kto zdobył najwięcej punktów w jednym meczu NBA (100)?
- `SPORT-0089` — Sporty zimowe / Polska / Ekspert: Na jakiej skoczni Wojciech Fortuna zdobył złoto olimpijskie w 1972 roku?
- `SPORT-0091` — Piłka nożna / Świat / Ekspert: Kto strzelił zwycięskiego gola w finale mistrzostw świata 2010?
- `SPORT-0105` — Sporty zimowe / Polska / Łatwy: W jakiej dyscyplinie medale olimpijskie zdobywał Adam Małysz?
- `SPORT-0153` — Sporty zimowe / Polska / Trudny: W którym roku Justyna Kowalczyk zdobyła złoto olimpijskie na 30 km stylem klasycznym?
- `SPORT-0189` — Koszykówka / Świat / Ekspert: Kto prowadził reprezentację USA „Dream Team” w turnieju koszykówki mężczyzn na igrzyskach w Barcelonie w 1992 roku?
- `SPORT-0207` — Sporty motorowe / Świat / Ekspert: Który kierowca wygrał Grand Prix Monako F1 w 1984 roku?
- `SPORT-0228` — Piłka nożna / Świat / Trudny: W którym roku po raz pierwszy o awansie w meczu piłkarskich mistrzostw świata zdecydowała seria rzutów karnych?
- `SPORT-0231` — Sporty zimowe / Polska / Ekspert: Który polski biegacz narciarski zdobył brąz na 30 km na igrzyskach w Vancouver 2010?
- `SPORT-0232` — Sporty zimowe / Polska / Ekspert: Który polski skoczek zdobył brąz olimpijski na dużej skoczni w Salt Lake City 2002?
- `SPORT-0240` — Sporty zimowe / Świat / Trudny: Który kraj wygrał najwięcej złotych medali na zimowych igrzyskach w Pekinie 2022?
- `SPORT-0245` — Koszykówka / Polska / Ekspert: W którym roku Polska zdobyła brązowy medal EuroBasketu mężczyzn po raz ostatni w XX wieku?
- `SPORT-0248` — Koszykówka / Świat / Łatwy: Po ilu faulach zawodnik musi opuścić mecz koszykówki według przepisów FIBA?
- `SPORT-0255` — Koszykówka / Świat / Trudny: Która reprezentacja wygrała mistrzostwa świata FIBA mężczyzn w 2023 roku?
- `SPORT-0274` — Siatkówka / Polska / Trudny: Który polski siatkarz był MVP mistrzostw świata w 2018 roku?
- `SPORT-0305` — Sporty motorowe / Polska / Normalny: Jak nazywa się indywidualny mistrz świata na żużlu z Polski z 2010 roku?
- `SPORT-0331` — Sporty zimowe / Polska / Normalny: Który polski skoczek zdobył złoto olimpijskie w Sapporo w 1972 roku?
- `SPORT-0344` — Lekkoatletyka / Polska / Łatwy: Który Polak zdobył złoto olimpijskie w pchnięciu kulą w Londynie 2012?
- `SPORT-0349` — Lekkoatletyka / Świat / Łatwy: W jakim mieście Usain Bolt ustanowił rekord świata 9,58 s na 100 metrów w 2009 roku?
- `SPORT-0350` — Lekkoatletyka / Polska / Normalny: Który polski kulomiot zdobył dwa złote medale olimpijskie z rzędu?
- `SPORT-0390` — Koszykówka / Świat / Trudny: Który kraj wygrał mistrzostwa świata w koszykówce mężczyzn w 2019 roku?
- `SPORT-0416` — Tenis / Polska / Ekspert: Który polski tenisista wygrał Australian Open w deblu w 1978 roku?
- `SPORT-0429` — Sporty zimowe / Polska / Ekspert: Który polski skoczek narciarski zdobył złoto olimpijskie na dużej skoczni w Pjongczangu 2018?
- `SPORT-0435` — Lekkoatletyka / Świat / Trudny: Kto zdobył złoty medal olimpijski w biegu na 800 m mężczyzn w Moskwie w 1980 roku?
- `SPORT-0451` — Koszykówka / Świat / Normalny: Ile minut trwa dogrywka w koszykówce według przepisów FIBA?
- `SPORT-0463` — Lekkoatletyka / Świat / Normalny: Ile płotków musi pokonać zawodnik w biegu na 400 metrów przez płotki?
- `SPORT-0512` — Siatkówka / Polska / Łatwy: W którym roku Polska zdobyła mistrzostwo świata siatkarzy na turnieju organizowanym we Włoszech i Bułgarii?
- `SPORT-0583` — Sporty zimowe / Świat / Ekspert: Który kraj wygrał złoto olimpijskie w curlingu mężczyzn w Pjongczangu 2018?
- `SPORT-0607` — Koszykówka / Świat / Łatwy: Jaki jest promień łuku wyznaczającego linię rzutów za trzy punkty według FIBA?
- `SPORT-0609` — Koszykówka / Świat / Normalny: Ile sekund ma zawodnik na wykonanie rzutu wolnego od chwili otrzymania piłki od sędziego według FIBA?
- `SPORT-0623` — Koszykówka / Świat / Ekspert: Który klub wybrał Dirka Nowitzkiego w drafcie NBA w 1998 roku?
- `SPORT-0681` — Piłka nożna / Polska / Trudny: W którym mieście rozegrano słynny „mecz na wodzie” Polska–RFN podczas mundialu 1974?
- `SPORT-0735` — Sporty motorowe / Polska / Ekspert: Kto wygrał Rajd Dakar 2024 w kategorii samochodów?
- `SPORT-0752` — Sporty motorowe / Świat / Ekspert: Jak nazywał się pierwszy zakręt pokonywany przez kierowców podczas inauguracyjnego wyścigu mistrzostw świata F1 na Silverstone w 1950 roku?
- `SPORT-0775` — Sporty zimowe / Polska / Trudny: Który kraj zdobył złoto w olimpijskiej sztafecie mieszanej w short tracku w Pekinie 2022?
- `SPORT-0777` — Sporty zimowe / Polska / Trudny: Która Polka zajęła 6. miejsce w biegu na 1500 m w łyżwiarstwie szybkim na igrzyskach w Soczi w 2014 roku?
- `SPORT-0830` — Koszykówka / Świat / Trudny: Ile sekund może trwać podstawowy limit na wyprowadzenie piłki z pola obrony na pole ataku w koszykówce FIBA?
- `SPORT-10006` — Lekkoatletyka / Polska / Normalny: Kto zdobył pierwszy złoty medal olimpijski dla Polski?
- `SPORT-10012` — Lekkoatletyka / Polska / Normalny: Która Polka ustanowiła rekord świata 82,98 m w rzucie młotem?
- `SPORT-10071` — Ogólne / Polska / Ekspert: W jakiej konkurencji Józef Zapędzki zdobywał olimpijskie złoto w 1968 i 1972 roku?

## Zalecenia
1. Dla każdego rekordu odnaleźć źródło pierwotne (federacja, oficjalny regulamin lub archiwum zawodów), sprawdzić odpowiedź i trzy dystraktory, dopiero potem zapisać URL.
2. Jeżeli nie można odtworzyć dowodu weryfikacji, zmienić status na `do_weryfikacji` w gałęzi roboczej, po odrębnej kontroli.
3. Nie modyfikować `main` ani GitHub Pages. W tej iteracji nie ingerowano w treść bazy.

## Kontrole ograniczone
Nie przeprowadzono pełnej weryfikacji faktów, semantycznej deduplikacji wszystkich 1850 rekordów ani testu HTTP źródeł. Liczba pytań NBA wymaga ręcznej klasyfikacji.