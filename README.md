# Obligatorisk oppgave 2 i Algoritmer og Datastrukturer

Denne oppgaven er en innlevering i Algoritmer og Datastrukturer. 
Oppgaven er levert av følgende studenter:
* Kristoffer Solberg, S331305, s331305@oslomet.no

# Arbeidsfordeling

I oppgaven har vi hatt følgende arbeidsfordeling:
* Jeg har løst alle oppgavene på egenhånd.

# Oppgavebeskrivelse

I oppgave 1 så fylte jeg inn antall metoden med det som sto i oppgaven, og det samme for tom-metoden. Deretter lagde
jeg konstruktøren uten om å bruke leggInn-metode. Fremgangsmåten på kontstruktøren var å følge specsa til konstruktøren
slavisk. 

I oppgave 2a lagde jeg en toString-metode med hjelp av Stringbuilder som beskrevet i oppgaven. Hadde med en sjekk for om 
lista var tom, og den tar med alle verdiene i lista frem til p er null.Gjorde akkurat det samme for omvendtString 
bortsett fra at man starter på halen og legger til den forrige igjennom hele lista. 
I oppgave 2b fulgte jeg oppgavebeskrivelsen og brukte requireNonNull, samtidig var oppgaven ganske grei når man hadde
en sjekkliste man kunne gå igjennom. Så å sørge for at man har checka av alle punktene i sjekklista gjør mye av jobben.

I oppgave 3a satt jeg en midtindeks som skulle være antall/2. Så lagde jeg en to if-tester for å sjekke om jeg skal 
begynne fra hode og gå til høyre eller hale og gå til venstre. Jeg brukte en teller for å løpe mot høyre eller venstre.
I hent-metoden så sjekker jeg indeksen ved å bruke indekskontroll og returnerer finnNode-metodens verdi.
I metoden oppdater så gikk jeg frem ved å sette opp punktene 1. find node with given index, 2. update values, 3. dont 
add null values, 4. increase endinger. Brukte requireNonNull og indekskontroll for sjekkene.
I oppgave 3b mener jeg at jeg henta fratilKontroll fra kompendiet (husker ikke helt). I subliste-metoden så bruker jeg
fra til kontroll, lagde en ny DobbeltLenketListe. Gjør en sjekk på om fra og til er lik.

I oppgave 4 skulle man lage indeksTil-metoden og inneholder-metoden. I indeksTil så sjekka jeg om verdi = null og 
returnerte -1 hvis det var tilfelle. Jeg satt current til hode og satt en teller. Lagde en while-loop for current ikke 
lik null. I inneholder-metoden fikk vi tips om å bruke indeksTil-metoden. Så jeg sa gjorde det og sjekka om verdien != 
-1. Hvis det var tilfelle returneres true.

I oppgave 5 her fulgte jeg hele sjekklisten til punkt å prikke. Kløna ekstremt mye med å holde tunga rett i munnen på 
alle .neste og .forrige tingene. Klarte til slutt å få det til å gi mening og løse det.

I oppgave 6 gjorde jeg det samme som tidligere oppgaver. I og med at dokumentasjonen er såpass bra så vet man ganske 
klart hva man skal gjøre, det største problemet er bare å få til alt som står i dokumentasjonen. Brukte indeksKontroll 
her også, og jeg brukte masse if-tester for å sjekke de forskjellige tingene som sto i sjekklista.

I oppgave 8a skulle jeg lage next-metoden. Da satt jeg if-tester på det som sto i oppgaveteksten og satt fjernOK = true,
satte nodeVerdi = denne.verdi og denne = denne.neste. Returnerte til slutt nodeVerdi.
I oppgave 8b skulle jeg returnere en instans av iteratorklassen, så da returnerte jeg new DobbeltlenketListeIterator.
I oppgave 8c satt jeg denne = finnNode(indeks), fjernOK = false og iteratorendringer = endringer. 
I oppgave 8d skulle jeg sjekke om indeksen er lovlig ved bruk av indeksKontroll og returnere en instans av 
iteratorklassen. Dette gjorde jeg ved return new DobbeltLenketListeIterator(indeks).
I oppgave 8 sleit jeg med å få testene til å fungere og fant ut at de var avhengige av nullstill-metoden, som jeg ikke 
skulle kode fordi jeg jobba aleine. Derfor måtte jeg endre litt i testene. Jeg har lagt inn kommentar i test-klassen for
hva jeg har gjort.
