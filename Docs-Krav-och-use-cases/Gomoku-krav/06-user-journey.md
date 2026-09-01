# User Journey - Gomoku
## Kort översikt:
Nedan finns User journeys som beskriver hur en användare upplever och interagerar med systemet från början till slut när användaren försöker att uppnå ett specifikt mål i systemet. 

Följande User journeys för Gomoku har tagits fram för att representera de viktigaste sätten som spelet används på:

* UJ-01: En gäst spelare som spelar mot dator
* UJ-02: En spelare som bjuder in en vän
* UJ-03: Spelare återupptar en pågående match.

Det som framför allt visas är användarens aktiviteter, systemets aktiviteter och användarens förväntade upplevelse under de olika stegen som sker i systemet
  
# UJ-01-Gäst spelare kör mot datorn
### Aktör: En gäst spelare
## Mål: Spelaren vill kunna köra en Gomoku match mot datorn samt kunna vinna, förlora eller spela oavgjort. 
```mermaid
journey
    title UJ-01: Gäst spelar en match mot datorn

    section Öppna spelet
      Öppnar Gomoku i webbläsaren: 5: Gäst
      Kan börja spela utan konto: 5: Gäst

    section Välj spelläge
      Väljer att spela mot datorn: 5: Gäst
      Systemet startar en ny match: 5: System

    section Välj svårighetsgrad
      Ser alternativen lätt, medel och svår: 5: Gäst
      Väljer svårighetsgrad: 5: Gäst
      Systemet använder vald svårighetsgrad: 5: System

    section Spela matchen
      Ser spelplanen: 5: Gäst
      Gör ett drag: 5: Gäst
      Väntar på datorns drag: 4: Gäst
      Datorn gör sitt drag: 4: AI
      Gör nästa drag: 5: Gäst
      Systemet hanterar turordningen: 5: System

    section Matchen avslutas
      Systemet kontrollerar fem i rad: 5: System
      Systemet kontrollerar om spelet är oavgjort: 5: System
      Resultatet visas: 5: Gäst
      Matchen avslutas: 5: Gäst
```
# UJ-02 – spela med vän i Gomoku
### Aktör: En gäst spelare
### Sekundär aktör: En vän
## Mål: Spelaren vill kunna starta en Gomoku-match med sin vän genom att dela en spellänk.
```mermaid
journey
    title UJ-02: Gäst bjuder in en vän och spelar

    section Öppna
      Öppnar Gomoku i webbläsaren: 5: Gästspelare
      Kan spela utan konto: 5: Gästspelare

    section Skapa match
      Väljer att spela med en vän: 5: Gästspelare
      Systemet skapar en match: 5: System
      Systemet skapar en spellänk: 5: System

    section Bjud in
      Kopierar spellänken: 5: Gästspelare
      Skickar länken själv till vännen: 5: Gästspelare
      Vännen öppnar länken: 5: Vän
      Vännen ansluter utan konto: 5: Vän

    section Spela
      Första spelaren gör ett drag: 5: Spelare
      Andra spelaren gör ett drag: 5: Vän
      Systemet hanterar turordningen: 5: System
      Systemet kontrollerar fem i rad: 5: System

    section Avsluta
      Vinnaren visas: 5: Spelare
      Oavgjort visas: 4: Spelare
      Spelarna kan starta en ny match: 5: Spelare
```
# UJ-03 – pausa och fortsätta en match
### Aktör: En spelare
## Mål: Spelaren vill kunna lämna ett pågående spel och fortsätta det senare från samma läge.
```mermaid
journey
    title UJ-03: Spelaren pausar och fortsätter en match

    section Spela
      Spelaren startar en match mot datorn: 5: Spelare
      Spelaren gör flera drag: 5: Spelare
      Matchen pågår: 5: Spelare

    section Pausa
      Spelaren vill sluta spela en stund: 4: Spelare
      Spelaren lämnar matchen: 4: Spelare
      Systemet sparar det pågående spelet: 5: System

    section Komma tillbaka
      Spelaren öppnar Gomoku igen: 5: Spelare
      Spelaren väljer det tidigare spelet: 5: Spelare
      Systemet laddar det sparade spelet: 5: System

    section Fortsätta
      Spelplanen visas i samma skick: 5: Spelare
      Spelaren fortsätter matchen: 5: Spelare
```
# 
