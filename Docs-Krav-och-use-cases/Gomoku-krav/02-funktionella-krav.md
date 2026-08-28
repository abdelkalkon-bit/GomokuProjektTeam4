# Funktionella Krav

## User Story

Som en spelare vill jag spela Gomoku mot en motståndare tills en av oss får fem i rad eller att spelet slutar i oavgjort.

## Spelet laddas

| ID       | Krav |
|----------|------|
| FR-01.1  | Systemet ska tillåta att en spelare går med i spelet. |
| FR-01.2  | Systemet ska kunna identifera om spelet är mot datorn, hot-seat multiplayer eller online multiplayer. |
| FR-01.3  | Systemet ska kunna ladda en spelplan av förvald storlek. | 
| FR-01.4  | Systemet ska kunna tilldela korrekt markör till spelare. | 
| FR-01.5  | Systemet ska automatiskt ange vilken spelare som börjar utifrån tilldelad markör. |

## Spel mot datorns AI

| ID       | Krav |
|----------|------|
| FR-02.1  | Systemet ska kunna tillåta att en spelare går med i spelet mot datorns AI. |
| FR-02.2  | Systemet ska låta spelaren välja svårighetsgrad, "lätt", "medium" eller "svårt". |
| FR-02.3  | Systemet ska kunna identifiera vilken svårighetsgrad som valts. |
| FR-02.4  | Systemet ska kunna ladda en spelplan av förvald storlek. | 
| FR-02.5  | Systemet ska kunna tilldela korrekt markör till spelaren. |
| FR-02.6  | Systemet ska automatiskt ange om spelaren eller om datorns AI börjar utifrån tilldelad markör. |
| FR-02.7  | Śystemet ska tillåta spelare 1 att placera sin markör på en tom punkt på spelplanen. | |
| FR-02.8  | Systemet ska hantera turordning mellan spelaren och datorn. |
| FR-02.9  | Systemet ska automatisk identifiera när spelaren eller datorns AI får 5 i rad. |
| FR-02.10 | Systemet ska automatikst avsluta spelet när spelaren eller datornn AI fått fem i rad och deklarera vinnaren. |
| FR-02.11 | Systemet ska automatiskt identifiera när spelplanen är full och ingen fått fem i rad. |
| FR.02.12 | Systemet ska automatiskt avsluta spelet när spelplanen är full och deklarera oavgjort. |

## Välj svårighetsgrad

| ID       | Krav | 
|----------|------|
| FR-03.1  | Systemet ska visa en meny med svårighetsgraderna "lätt, "medel" och "svår" när spelaren väljer att spela mot datorn. |
| FR-03.2  | Systemet ska låta spelaren välja en av svårighetsgraderna. |
| FR-03.3  | Systemet laddar ett spel med den valda svårighetsgraden. |

## Spela anonymt utan konto

| ID       | Krav |
|----------|------|
| FR-04.1  | Systemet ska låta en ny användare öppna Gomoku i en webbläsare. |
| FR-04.2  | Systemet ska låta användaren starta ett spel utan registrarat konto. |
| FR-04.3  | Systemet ska låta användaren starta ett spel utan att användaren behöver vara inloggad. |
| FR-04.4  | Systemet ska tillåta användaren att välja spelläge utan att samla in personlig information. |
| FR-04.5  | Systemet ska tillåta användaren att starta ett spel utan att kräva personlig information. |
| FR-04.6  | Systemet ska tillåta användaren att spela ett parti från start till slut utan att samla in personlig information. |

## Användaren hanterar Cookies

| ID       | Krav |
|----------|------|
| FR-05.1  | Systemet ska tillåta att en användare öppnar Gomoku via en webbläsare. |
| FR-05.2  | Systemet ska kunna informera om hemsidan använder cookies eller annan typ av spårning. |
| FR-05.3  | Systemet ska inte automatiskt samal in information om användaren utan samtycke. |
| FR-05.4  | Systemet ska låta användaren godkänna eller neka cookies och samt annat som kräver godkännande. |
| FR-05.5  | Systemet ska låta användaren spela Gomoku även när cookies nekats. |

## Bjud in vän via länk

| ID       | Krav |
|----------|------|
| FR-06.1  | Systemet ska generera en invite länk när användaren skapar ett spel. |
| FR-06.2  | Systemet ska låta användaren kopiera länken. |
| FR-06.3  | Systemet ska låta användaren själv skicka länken till en annan användare. |
| FR-06.4  | Systemet ska omdirigera användaren till ett spel när hen klickar på en invite länk. |
| FR-06.5  | Systemet ska låta användaren spela ett spel via invite länken utan att hen behöver ha befintligt konto eller logga in. |




## Spelet körs

| ID       | Krav |
|----------|------|
| FR-02.1  | Spelaren ska kunna placera sin markering på en ledig punkt förutsatt att det är spelarens tur. |
| FR-02.2  | Spelet ska neka att en markering placeras på en upptagen punkt. |
| FR-02.3  | Spelet ska hantera turordning mellan spelare. |

## Vinst

| ID       | Krav |
|----------|------|
| FR-03.1  | Spelet ska kunna identifiera när fem markeringar av samma sort ligger i rad. |
| FR-03.2  | Spelet ska kunna identifiera vilka markeringar som hör till vilken spelare. |
| FR-03.3  | Spelet ska identifiera vinnare utifrån vilka markeringar som fått fem i rad. |
| FR-03.4  | Spelet ska avslutas automatiskt när en spelare vunnit. |
| FR-03.5  | En skärm ska visa vilken spelare som vann och innehålla knappar för huvudmeny och ny match. |
| FR-03.6  | Spelaren ska kunna återgå till huvudmenyn efter avslutat spel. |
| FR-03.7  | Spelaren ska kunna starta en ny match efter avslutat spel. |

## Oavgjort

| ID       | Krav |
|----------|------|
| FR-04.1  | Spelet ska kunna identifiera när brädet är fullt och ingen spelare fått fem i rad. |
| FR-04.2  | Spelet ska avslutas när brädet är fullt och ingen spelare fått fem i rad. |
| FR-04.3  | En skärm ska visa "oavgjort" och ha knappar för huvudmeny och nytt parti. |
| FR-04.4  | Spelaren ska kunna återgå till startmenyn efter avslutat spel. |
| FR-04.5  | Spelaren ska kunna starta ett nytt parti efter avslutat spel. |

