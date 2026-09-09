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


