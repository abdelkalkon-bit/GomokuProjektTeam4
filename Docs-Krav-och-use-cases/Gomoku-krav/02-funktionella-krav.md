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

