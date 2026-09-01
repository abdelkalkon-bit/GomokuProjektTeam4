

# Användningsfall 10 - Gomoku

## UC-10: Se matchresultat i Gomoku

| Fält              | Värden                         |
|-------------------|--------------------------------|
| Use Case ID       | UC-10                          |
| Namn              | Avsluta pågående match i Gomoku |
| Version           | 1.0                            |
| Preliminär Aktör  | Gäst User, Registrerad Användare |
| Sekundär Aktör    | AI motståndare, annan spelare  |
| Relaterad FR      | …                              |
| Relaterad NFR     | …                              |


Aktör: En spelare

Mål: Spelaren vill se om han/hon vann, förlorade eller om matchen slutade oavgjort

Förutsättningar: 
* Spelaren befinner sig i en pågående match
* Ett drag har precis genomförts av en av spelarna

Huvudflöde:
1. Spelaren gör ett drag på spelplanen.
2. Systemet kontrollerar om draget resulterar i fem i rad (horisontellt, vertikalt eller diagonalt).
3. Systemet identifierar att en spelare har uppnått fem i rad.
4. Systemet avslutar matchen och visar vinnaren för båda spelarna.

Alternativa flöden:
* 3a. Oavgjort: Om spelplanen blir full utan att någon spelare uppnått fem i rad, avslutar systemet matchen och meddelar att resultatet blev oavgjort.
* 3b. Motståndaren lämnar matchen:** Om motståndaren avbryter eller lämnar matchen innan den är avslutad, meddelar systemet att spelaren vinner matchen genom walkover.

Förväntat resultat:
Matchen avslutas och resultatet (vinst, förlust eller oavgjort) visas tydligt för spelaren. Spelplanen låses för vidare drag och spelaren får möjlighet att starta en ny match.


