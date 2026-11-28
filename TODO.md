# Att göra längre fram

Arbetssätt: nya önskemål samlas här och släpps som en större version (v1.1, v1.2 …). Buggfixar släpps direkt.

## Till v1.3 (läsmålen och flera sätt att få tag i en bok, klar till nyår)
- Bestäm läsmålen för 2027 (förslag: antal böcker, sidor, från backloggen, på svenska, Hugo/Nebula-vinnare) och vilka gränser som ger grön, gul och röd.
- Hem: toppraden byggs om till läsmålen. Hem svarar på "hur går det just nu?", Statistik på "hur har det gått?". En ruta per mål med markering och siffra (t.ex. "16 / 50"), plus Hela listan. Klick leder till målen under Plan. Jämförelser mot förra året finns bara i Statistik.
- Plan: kortet Läsmål med varje mål, stapel och förklaring (enligt skissen från 27 nov).

- Tillgång (bokkortet, enligt skiss 28 nov): en del "Tillgång" med en rad per sätt att få tag i boken. Typer: Kö, Notify, Lån, Lokal fil, Fysisk bok. Samma typ kan finnas flera gånger (t.ex. kö på två bibliotek). Biblioteksrader visar bibliotek, "Libby" om boken finns där, och väntetid/beräknat datum för köer. Knappar per rad: Kö → Lånad, Notify → I kö, alla → Ändra, Ta bort. "Lägg till: Kö, Notify, Lån, Lokal fil, Fysisk bok". Ersätter fälten Status, Källa, Format, Libby, Lånedatum och Väntetid. Bibliotek visas först, lokal fil och fysisk bok som reserv.
- Hem, Lån och köer: visar alltid lån, köer och notify, även när lokal fil finns ("I kö · ca 12 jan (6 v) · lokal fil finns", "Notify · Broward" med knappen I kö).
- Börja läsa: frågar "Hur läser du den?" bland bokens tillgångar (finns bara ett sätt: ingen fråga). Väljer man ett befintligt lån ändras inte lånedatumet. Väljer man en kö blir den ett lån (lånedatum idag, går att ändra). Svaret sparas som Läser via.
- Läst klart: ingen fråga om Läser via redan finns (annars frågas en gång). Biblioteksrader utom den som användes tas bort automatiskt (andra köer, notify, lån); lånet som användes sparas som Läst via och tas bort som aktivt lån. Lokal fil och fysisk bok ligger kvar. Sedan betyg och "Läsa mer av …?" som i dag. Boken flyttas till Lästa, räknas i året och planen.
- Statistikens Källa bygger på Läst via.
- Flytt av data: lästa böcker behåller sin källa som Läst via; olästa får sin nuvarande status, källa, format, Libby, lånedatum och väntetid som första tillgång. Testas i beta.

## Senare
- Testa export i samma format som TBR-fliken i arket (samma kolumner och ordning), så att listan kan klistras in där vid behov.

- Goodreads Choice 2026: plats 1–3 i de kategorier som redan finns, när vinnarna är klara (påminnelse 10 december).
- Kanske: helt automatisk bevakning via GitHub med notiser (kräver Firebase-nyckel hos GitHub).
