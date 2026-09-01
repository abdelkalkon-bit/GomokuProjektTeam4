# Användningsfall 08 - Gomoku

## UC-08 Avsluta pågående match i Gomoku

| Fält              | Värden                         |
|-------------------|--------------------------------|
| Use Case ID       | UC-08                          |
| Namn              | Avsluta pågående match i Gomoku |
| Version           | 1.0                            |
| Preliminär Aktör  | Gäst User, Registrerad Användare |
| Sekundär Aktör    | AI motståndare, annan spelare  |
| Relaterad FR      | …                              |
| Relaterad NFR     | …                              |

Aktör: En spelare.

Mål: Spelare vill avsluta pågående Gomoku match.

Förutsättningar: Spelaren är inne i ett pågånde spel.

### Huvudflöde

1. Spelaren väljer att avsluta pågående spel mot datorn eller annan spelare.
2. Spelaren får upp en bekräftelseruta med valen "Avsluta match" och "Fortsätt spela".
3. Spelaren väljer "Avsluta match".
4. Brädet fryser.
5. Avslutningsskärm poppar upp med texten "Match avslutad" samt valen "Spela igen" och "Till huvudmeny".

### Förväntat resultat

Brädet fryser i det senaste läget det befann sig i, spelet avslutas och användaren får upp en avslutningsskärm med texten "Match avslutad" samt valen "Spelaigen" och "Till huvudmeny".



