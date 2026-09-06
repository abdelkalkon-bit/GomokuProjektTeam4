# Användningsfall 09 - Gomoku

## Spelare vill fortsätta pausad match

| Fält          | Värden         |
|---------------|----------------|
| Use Case ID   | UC-09      |
| Namn          | Spelare vill fortsätta pausad match |
| Version       | 1.0        |
| Preliminär Aktör | Gäst User, Registrerad Användare |
| Sekundär Aktör | AI motståndare, annan spelare i lokal multiplayer |
| Relaterad FR | FR-09.1, FR-09.2 |
| Relaterad NRF | NFR-01, NFR-03 |

## Aktör:
En spelare.

## Mål:
Spelaren vill återgå till en pausad match mot datorn eller lokal multiplayer.

### Förutsättningar:
- Spelaren har pausat ett påbörjat spel mot datorn eller en mot annan spelare i lokal multiplayer.

# Huvudflöde

1. Spelaren väljer att pausa ett pågående spel mot datorn eller i lokal multiplayer.
2. Brädet fryser
3. Pausmeny med tre val poppar upp: "Forstätt", "Spara och avsluta" (endast mot datorn), "Till huvudmeny".
4. Spelaren väljer "Fortsätt".
5. Spelbrädans tillstånds är identiskt som det var innan spelet pausades
6. Turordningen hanteras korrekt

# Förväntat resultat

Brädet fryser i det senaste läget innan spelet pausades. Pausmeny poppar upp med tra val: "Fortsätt", "Spara och avsluta" (om spelaren spelar mot datorn), och "Till huvudmeny". Spelaren väljer "Fortsätt" och spelet uppstår från att vara fryst. Spelbrädets tillstånd är identiskt som det var innan spelet pausades. Turodningen hanteras korrekt.
