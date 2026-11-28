# Versionshistorik

Bokhyllan: https://kittykatten.github.io/bokhyllan/

Versionsnumret syns längst ner under **Mer**. Nya önskemål samlas i [TODO.md](TODO.md) och släpps som en större version. Buggfixar släpps direkt som v1.0.1, v1.0.2 och så vidare.

## v1.2 – 28 november 2026

**Läser nu**
- Klicka på dagrutan och fyll i hur långt du har läst, i procent eller som sida. Rutan visar "40 % läst" med heldragen stapel; dagarna efter räknar appen vidare och visar "beräknat läst" med ljus stapel.
- Beräknat slutdatum räknas om från sidorna som är kvar, med en blandning av din takt i boken och ditt snitt för bokens språk. Ju mer du har läst, desto mer väger boken själv.
- Läst klart sätter 100 %. Går även i mobilen.

**Statistik**
- Listan per år som ett kompakt kort i den lediga platsen bredvid Betyg.
- Böcker i år delad i romaner och noveller, med var sin jämförelse mot förra året.

**Inkorgen**
- Datum för senaste sökningen efter nya böcker.
- Rättade författarnamn och avlidna författare (Wikidata) blir förslag att godkänna i stället för att ändras direkt.

**Bokvyn**
- Betyg visas bara för lästa böcker.
- Tidigare läst och Lägg till läsning ligger under ✎ Redigera.

## v1.1.2 – 28 november 2026

**Läser nu**
- Snitt per bok är borttaget. Det räknades på ett annat sätt än slutdatumet och gav intryck av att man låg efter.
- I stället: hur många procent av boken du beräknas ha läst, med en tunn stapel, och beräknat slutdatum.
- Beräkningen använder din lästakt för böcker på samma språk som den du läser.
- Bok #43 i stället för #43.

## v1.1.1 – 27 november 2026

**Buggfixar**
- Hem i mobilen: Plan för månaden visar också böcker du läser och böcker som inte finns i listan. Den sa "Allt i planen är läst" fast det inte var det.
- Hem i mobilen: kortet med lån och köer heter Lån och köer (eller I kö), som på datorn.

## v1.1 – 27 november 2026

**Hem på datorn**
- Ny ruta i översta raden: Läsmål, med grön, gul eller röd markering och länk till Plan. Visar "Inte satta än" tills målen finns.
- Läser nu är en remsa över hela bredden. Vid omslaget: sidor, utgivningsår, serie och lånedatum när boken är lånad. Sex uppgifter på fasta platser: dag (och snitt per bok), när du är klar i din takt, tid på listan innan du började, vilken bok av författaren det är, vilket nummer i år och i månaden, och läsmål.
- Knapparna Läst klart och Gav upp direkt på Hem.
- Tre kolumner under: Plan för den här månaden, Plan för nästa månad, Lån och köer.

**Hem i mobilen**
- Enklare startsida: en statusrad, Läser nu med knappar, månadens olästa planböcker med Börja, Att hålla koll på (lån och köer i datumordning) och knapparna Ny bok, Sök och Slumpa nästa.

**Köer**
- Nytt fält Väntetid (veckor) för böcker i kö. Appen visar ett beräknat datum, till exempel "I kö · ca 8 jan (6 v)", och sorterar kön efter det. Pausade köer får inget datum.
- Knappen Lånad på köade böcker gör om dem till lån med dagens datum.

**Plan**
- Kort för Läsmål överst, där målen kommer att visas.

**Mindre ikoner**
- Text i stället för ✓, ✕, + och ▶ på knappar, och ingen klocka före "på listan". Slumpa, Sök nya böcker nu, Libby-symbolerna i Böcker och ⏳/🎉 vid utgivning är kvar.

**Buggfixar**
- Markera som läst idag, Börja läsa idag och Lånad idag sparade inte alltid dagens datum när datumfältet syntes i bokvyn.

## v1.0 – 27 november 2026

Första versionen. Bokhyllan flyttade från arket och claude.ai till en egen app med data i Firebase.

**Grunden**
- Inloggning med Google, data i Firebase, installeras som app i mobilen.
- Arket är inte längre huvudkälla. Det finns kvar orört.
- Säkerhetskopia under Mer.

**Hem**
- Läser nu, Plan för månaden, Läsmål 2027 (tomt än) och Lån och köer.
- Dra en bok från Plan eller Lån och köer till Läser nu. På telefonen finns knappen ▶ Börja.
- Påminnelser när en bok släpps om en vecka eller idag.
- Hur lång tid det tar att läsa hela listan, med beräknat slutdatum.
- Bokhyllan i övre vänstra hörnet leder till Hem.

**Böcker**
- Visar alla böcker som standard. Flikar: Att läsa, Läser, Kommande, Backlog, Lästa, Alla.
- Filter för genre, språk, sidor, kön, nästa del i serie och Libby (finns, notify, finns inte, vet inte).
- Sortering Bäst förslag först och knappen 🎲 Slumpa.
- Etiketten ⏱ tid på listan.

**Bokvyn**
- Fasta uppgifter bakom ✎ Redigera, Goodreads-länk på faktaraden.
- Format, status och källa hänger ihop. Status Lånad fyller i lånedatum, och appen räknar ut när boken ska tillbaka.
- Knappar: Lånad idag, Börja läsa idag, Markera som läst idag, Flytta från listan med anledning, val av planmånad.
- Flera tidigare läsningar kan läggas till och tas bort.
- Datum visas med den exakthet som finns: år till och med 2015, månad till augusti 2023, därefter hela datumet.

**Serier**
- Status per bok: Läst, Läser, På listan, Bortvald eller Inte på listan. Titlar som inte finns hos dig länkar till Goodreads, och + På listan lägger till med ett klick.
- Saknade delar föreslås i Inkorgen, från Wikidata eller fasta listor från Goodreads.
- Wikidata räknas bara när boken uttryckligen är del av en serie. Tv-avsnitt, noveller, antologier och onumrerade sidoberättelser hoppas över.
- Avbrutna serier och fristående böcker i samma värld får inga förslag.

**Författare**
- Läsa mer av författaren: Ja, Kanske, Nej, Vet ej eller Avliden. Avlidna markeras via Wikidata.
- ✎ Byt namn på författarsidan. Felstavade och förkortade namn rättas.
- Böcker du lägger till själv påverkas aldrig av svaret om författaren.

**Inkorg**
- Allt som hittas automatiskt hamnar här för godkännande, aldrig direkt i en lista.
- Bokbevakning: nya och kommande böcker av Ja-författare från Open Library, en gång i veckan från måndag. Knappen Sök nya böcker nu finns också.
- Saknade seriedelar, serieförslag, nya i Hugo och Nebula, dubbletter, författarnamn och frågor om böcker som legat länge.

**Priser**
- Hugo, Nebula och Goodreads Choice som egna flikar.
- Filter för år, roman eller novell, Vann båda och Nominerad till båda.
- Hugo och Nebula uppdateras från Wikidata en gång i månaden.

**Statistik**
- Romaner och noveller för sig, jämförelse med samma tid förra året. Allt går att klicka på.
- Rekord, Mest lästa författare och kortet Listan per år: tillagda, lästa, borttagna, listans storlek och hur slutdatumet har ändrats.
