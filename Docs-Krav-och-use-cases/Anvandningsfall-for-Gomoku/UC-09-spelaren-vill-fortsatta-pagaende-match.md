# Användningsfall 09 - Gomoku

## Återuppta sparad match

| Fält          | Värden         |
|---------------|----------------|
| Use Case ID   | UC-09      |
| Namn          | Spelare vill fortsätta pausad match |
| Version       | 1.0        |
| Preliminär Aktör | En spelare |
| Sekundär Aktör | AI motståndare, annan spelare i lokal multiplayer |
| Relaterad FR | FR-09.1–FR-09.2|
| Relaterad NRF | NFR-01, NFR-03 |

## Aktör:
En spelare.

## Mål:
Spelaren vill återgå till en pausad match mot datorn eller lokal multiplayer.

### Förutsättningar:
- Spelaren har pausat ett påbörjat spel mot datorn eller en mot annan spelare i lokal multiplayer.

# Huvudflöde

1. Spelaren har ett tidigare sparat spel.
2. Spelaren väljer att fortsätta spelet.
3. Systemet laddar senaste sparade state.
4. Systemet visar spelbrädet.
5. Systemet återställer korrekt turordning.
6. Spelaren kan fortsätta spela.

# Förväntat resultat

Brädet fryser i det senaste läget innan spelet pausades. Pausmeny poppar upp med tre : "Fortsätt", "Spara och avsluta" (om spelaren spelar mot datorn), och "Till huvudmeny". Spelaren väljer "Fortsätt" och spelet uppstår från att vara fryst. Spelbrädets tillstånd är identiskt som det var innan spelet pausades. Turodningen hanteras korrekt.
