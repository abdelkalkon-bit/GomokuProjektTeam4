# USE CASES >> TEST CASES >> KVALITE. 
 Vi skapade olika testfall från våra användningsfall frö att säkerställa att systemet faktist fungerar som det är tankt ur användarens perspektiv. Våra användningsfall är beskriver ett tydligt mål med steg för att nå det. Detta är en perfekt mall för oss
 att utgå ifrån för att verifiera systemets funktionalitet och kontrollera kvalitet. 


# TC-01 – Starta en match
## Relaterat UC: 
UC-01
## Förutsättningar: 
Användaren är på startsidan.
# Steg:
1. Användaren väljer att starta en ny match.
2. Användaren väljer vilken typ av match som ska spelas.
3. Matchen startas.
# Förväntat resultat:
* En ny match skapas.
* Spelplanen visas.
* Två motståndare tilldelas.
* Spelarna får varsin markör.
* Systemet visar vem som börjar.

# TC-02 – Spela mot datorn
## Relaterat UC:
UC-02
## Förutsättningar:
En match mot datorn har startats.
# Steg:
1. Spelaren gör ett giltigt drag.
2. Spelaren väntar på datorns drag.
# Förväntat resultat:
* Spelarens sten placeras på den valda lediga platsen.
* Turen går över till datorn.
* Datorn gör ett giltigt drag.
* Turen går tillbaka till spelaren.

# TC-03 – Ogiltigt drag på upptagen position
## Relaterat UC:
UC-02
## Förutsättningar:
Det finns redan en sten på den valda positionen.
# Steg:
1. Spelaren försöker placera en sten på den upptagna positionen.
# Förväntat resultat:
* Systemet tillåterr inte att Stenen placeras inte.
* Den befintliga stenen påverkas inte.
* Det är fortfarande samma spelares tur.

# TC-04 – Spelare kan bara spela på sin tur
## Relaterat UC:
UC-02 / UC-07
## Förutsättningar:
En match är igång och spelare 1 har sin tur.
# Steg:
1. Spelare 1 gör ett giltigt drag.
2. Spelare 1 försöker göra ytterligare ett drag direkt.
# Förväntat resultat:
* Det andra draget nekas av systemet och turen går till spelare 2. 

# TC-05 – Fem i rad horisontellt
## Relaterat UC:
UC-02 / UC-10
## Förutsättningar:
En match är igång redan mellan två spelare eller dator.
# Steg:
1. Spela tills en spelare får fem egna stenar horisontellt i rad.
# Förväntat resultat:
* Systemet upptäcker fem stenar i rad.
* Rätt spelare utses som vinnare.
* Matchen avslutas.

# TC-06 – Fem i rad vertikalt
## Relaterat UC:
UC-02 / UC-10
## Förutsättningar:
En match är igång.
# Steg:
1. Spela tills en spelare får fem egna stenar vertikalt i rad.
# Förväntat resultat:
* Systemet upptäcker fem stenar i rad.
* Rätt spelare utses som vinnare.
* Matchen avslutas.

# TC-07 – Fem i rad diagonalt
## Relaterat UC:
UC-02 / UC-10
## Förutsättningar:
En match är igång.
# Steg:
1. Spela tills en spelare får fem egna stenar diagonalt i rad.
# Förväntat resultat:
* Systemet upptäcker fem stenar i rad.
* Rätt spelare utses som vinnare.
* Matchen avslutas.

# TC-08 – Inga drag efter en vinst
## Relaterat UC:
UC-10
## Förutsättningar:
En spelare har redan vunnit matchen.
# Steg:
1. Försök placera ytterligare en sten..
# Förväntat resultat:
* Draget accepteras inte.
* Matchen förblir avslutadd.

# TC-09 – Oavgjort
## Relaterat UC:
UC-10
## Förutsättningar:
Spelplanen kan fyllas utan att någon får fem i rad.
# Steg:
1. Fyll hela spelplanen.
# Förväntat resultat:
* Systemet upptäcker att spelplanen är full.
* Matchen avslutas som oavgjord.
* Det visas att matchen blev oavgjord.

# TC-10 – Starta ny match efter avslutad match
## Relaterat UC:
UC-10
## Förutsättningar:
En match har avslutats genom vinst eller oavgjort.
# Steg:
1. Välj "Ny match".
# Förväntat resultat:
* En ny match startas.
* Spelplanen är tom.
* Den tidigare matchens spelstatus använnds inte.

# TC-11 – Välja svårighetsgrad
## Relaterat UC:
UC-03
## Förutsättningar:
Användaren kan välja svårighetsgrad innan matchen startas.
# Steg:
1. Öppna valet av svårighetsgrad.
2. Välj en svårighetsgrad.
3. Starta matchen.
# Förväntat resultat:
* Den valda svårighetsgraden används i matchen.

# TC-12 – Spela anonymt
## Relaterat UC:
UC-04
## Förutsättningar:
Användaren har inget konto.
# Steg:
1. Starta spelet utan att skapa ett konto.
2. Starta occh spela en match.

# Förväntat resultat:
* Spelaren kan starta en match utan konto.
* Spelaren kan spela hela matchen utan att logga in.

# TC-13 – Hantera cookies
## Relaterat UC:
UC-05
## Förutsättningar:
Spelet visar valet för cookies.
# Steg:
1. Öppna spelet.
2. Välj att acceptera cookies.
3. Starta en match.
4. Gör om testet och neka cookies.
# Förväntat resultat:
* Användaren kan välja att acceptera eller neka cookies.
* Spelet går fortfarande att använda när cookies nekas.

# TC-14 – Skapa och kopiera spellänk
## Relaterat UC:
UC-06
## Förutsättningar:
Användaren kan skapa en online-match.
# Steg:
1. Skapa en online-match.
2. Kontrollera att en invite-länk visas.
3. Välj "Kopiera länk".
# Förväntat resultat:
* Matchen får ett match-ID.
* En spellänk visas.
* Länken går att kopiera.

# TC-15 – Ansluta till match via länk
## Relaterat UC:
UC-07
## Förutsättningar:
Spelare 1 har skapat en online-match och har en spellänk.
# Steg:
1. Spelare 1 skapar en online-match.
2. Spelare 2 öppnar den delade länken.
# Förväntat resultat:
* Spelare 2 ansluts till rätt match.
* Spelare 2 kan spela mot spelare 1.
* Båda spelarna ser samma match.

# TC-16 – Ansluta till ogiltig eller full match
## Relaterat UC:
UC-07
## Förutsättningar:
Det finns en ogiltig spellänk eller en match där två spelare redan deltar.
# Steg:
1. Öppna en ogiltig invite-länk eller försök ansluta till en full match.
# Förväntat resultat:
* Användaren kan inte ansluta till matchen.
* Ett tydligt felmeddelande visas.

# TC-17 – Hot-seat
## Relaterat UC:
UC-13
## Förutsättningar:
Användaren har valt hot-seat.
# Steg:
1. Välj hot-seat.
2. Spelare 1 gör ett drag.
3. Spelare 2 gör ett drag.
4. Fortsätt tills matchen avslutas.
# Förväntat resultat:
* Två spelare kan spela på samma enhet.
* Turordningen fungerar.
* Rätt spelare kan göra sitt drag.




