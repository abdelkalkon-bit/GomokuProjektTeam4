# Användingsfall 06 - Användaren bjuder in sin vän via en länk.
| Namn  | Värde |
|-------|-------|
|User case ID | UC-06 |
|Namn på filen| Användaren bjuder in sin vän via en länk |
|Aktör|guest spelare|
|Relaterade FR | .. |
|Relaterade NFR | Användbarhet |

## Relevant för GDPR: Data minimization samt Privacy/Transparency

Aktör: En spelare

Mål: Länken skapas och skickas utan att systemet spårar, loggar eller användardata på något sätt.

Förutsättning: Spelaren är på hemsidan för Gomoku och vill bjuda in sin kompis.

### Huvudflöde:

1. Spelaren skapar ett speel som vanligt och systemet genererar en invite länk.
2. Spelaren kopierar länken.
3. Spelaren skickar själv länken till sin vän.
4. Spelarens vän klickar på länken för att köra.
5. Spelarens vän kan delta i spelet utan att behöva skapa ett konto.

### Förväntat resultat av deenna GDPR-TEST:
Kontrollera att systemet inte skickar spelarens personuppgifter på något sätt eller någon annan tredje part bara för att skapa/skicka länken. 
