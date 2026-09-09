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


