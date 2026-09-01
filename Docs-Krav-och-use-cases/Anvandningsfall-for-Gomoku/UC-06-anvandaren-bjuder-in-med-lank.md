# Användingsfall 06 - Användaren bjuder in sin vän via en länk.
| Namn  | Värde |
|-------|-------|
|User case ID | UC-06 |
|Namn på filen| Användaren bjuder in sin vän via en länk |
|Version | 1.0 | 
|Aktör|en spelare|
|Sekundär aktör | En-vän |
|Relaterade FR | FR-06.1, FR-06.2, FR-04.2, FR-04.3, FR-04.5, FR-04.6, FR-07.2, |
|Relaterade NFR | NFR-06 Anslutning via länk, NFR-08 Säkerhet och integritet |

## Relevant för GDPR: Data minimization samt Privacy/Transparency

Aktör: En spelare

Mål: Spelaren ska kunna skapa en länk till en Gomoku match och dela den med sin vän utan att behöva lämna personuppgifter eller skapa ett konto i systemet. 

Förutsättning: Spelaren är på hemsidan för Gomoku och vill starta som hans vän ska kunna ansluta sig till. 

### Huvudflöde:

1. Spelaren startar en Gomoku match
1. Systemet skapar en länk som kan användas av en annan spelare för att ansluta till en match. 
2. Spelaren kopierar länken.
3. Spelaren skickar själv länken till sin vän.
4. Spelarens vän klickar på länken för att köra.
5. Spelarens vän kan delta i spelet utan att behöva skapa ett konto.

### Alternativa flöde:
- 
- 

### Förväntat resultat:
Kontrollera att systemet inte kräver personuppgifter eller konto från personen som anslutar via en länk. Kontrollera även att systemet inte samlar in personuppgifter och att användaren kan dela länken till en gomoku-match med sin vän. 
