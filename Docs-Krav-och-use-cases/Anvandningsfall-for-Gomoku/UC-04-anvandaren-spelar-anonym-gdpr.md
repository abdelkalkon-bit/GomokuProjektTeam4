# Användningsfall 04 - Användaren spelar anonymt utan konto

| Namn | Värde |
|-------|-------|
| Use case ID | UC-04 |
| Namn på filen | Användarene spelar anonymt utan konto |
| Version | 1.0 |
| Aktör | guest spelare |
| Sekundär akör | Ingen |
| Relaterade FR | FR-04.1,FR-04.2,FR-04.3,FR-04.4,FR-04.5,FR-04.6|
| Relaterade NRF | NFR-04 Anonym användning, NFR-08 Säkerhet och integritet |

## Relevant GDPR: Data minimization Privacy/Transparency

## Aktör: 
En spelare

## Mål: 
Säkerställa att systemet inte krväer personuppgifter från en spelare som inte är inloggad och som vill spela Gomoku. 

### Förutsättning: 
- Användaren öppnar Gomoku för första gången från en webbläsare
- Användaren behöver inte ha ett konto eller vara inloggad.

# Huvudflöde:

1. Användaren öppnar Gomoku för första gången från en webbläsare.
2. Systemet låter användaren starta ett spel utan att kräva konto eller inloggning. 
3. Användaren väljer spelläge och kan köra utan krav från systemet om personlig information.
4. Systemet kräver inte personuppgifter för att den ska fungera.
5. Användaren kan spela en hel Gomoku match från början till slut utan att behöva registrera ett konto eller logga in. 

### Alternativa flöde: 
- Användaren kan välja logga in om systemet visar det.
- Systemet låter användaren skapa eller ansluta till en match utan att kräva ett konto.
- Användaren kan fortsätta använda spelet utan att lämna personuppgifter. 

### Förväntat resultat: 
Användaren kan starta Gomoku och spela en match utan att behöva registrera ett konto, logg in eller lämna något personuppgifter. Systemet ska även inte kräva personuppgifter för att den ska fungera. 




