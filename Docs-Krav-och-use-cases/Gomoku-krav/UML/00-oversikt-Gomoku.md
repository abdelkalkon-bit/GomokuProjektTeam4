# UML - Översikt 

Den här mappen innehåller fleera UML-diagram som beskriver Gomoku-systemets struktur men även beteende och olika tillstånd.

Meningen med diagrammen är att använda de för en tydligare bild av systemets olika delar som samverkar samt hur en spelomgång fungerar.

#  För Sekvensdiagram:
Sekvensdiagrammet vi skapade visar hur olika objekt i systemet kommunicerar med varandra över tid. Det är alltså mer fokus på flöder när en spelare till exempel gör ett drag och hur systemet kontrollerar draget, uppdaterar spelplanen och sedan avgöra om spelet ska fortsätta eller avslutas.

# För Aktivitetsdiagram: 
Här finns det en arbetsflöde för en spelomgång, filen visar till exempel hur spelet startas, hur spelarna gör sina drag, hur dragen valideras och sedan hur systemet hanterar vinst, oavgjort eller att spelet fortsätter.

# För tillståndsdiagram 
I den filen beskriver vi mer de olika tillstånd som ett Gomoku-spel kan befinna sig i men även vilka händelser som leder till olika övergångar mellan tillstånden.

Det är mer fokus på till exempel att spelet väntar på att startas > att en spelare gör sitt drag > att draget kontrolleras > att spelet avslutas. Dessa tillstånd kan man verfiera att kontrollera att spelets tillstånd förändras. 

# Kort sammanfattning:

- Sekvensdiagrammet: Visar kommunikation mellan systemets delar.
- Aktivitetsdiagrammet: Visar arbetsflödet mer i detalj.
- Tillståndsdiagrammet: Visar hur spelets tillstånd förändras. 

## Diagrammen kan användas som stöd för utveckling, testning och dokumentation av systemet. 