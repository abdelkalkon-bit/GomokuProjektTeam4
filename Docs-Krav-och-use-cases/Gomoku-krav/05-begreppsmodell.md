# Begreppsmodell

## Följande begrepp är viktiga för Gomoku och har en relation till spelets funktion:

 1. Sten
 2. Spelplan
 3. position
 4. Spelare
 5. Spel
 6. Match
 7. Drag
 8. Tur
 9. Resultat
 10. Spelinbjudan
 11. Svårighetsgrad

## Relationer för dem olika begreppen kan bland annat vara:

- En spelare deltar i ett Gomoku spel
- Ett Gomoku spel har en spelplan att spela på
- En spelplan består av olika positioner
- En spelare gör ett drag mot sin motståndare 
- Ett drag placerar en sten från en position till en annan.
- En Gomoku match har olika turer mellan varandra.
- En tur tillhör endast en spelare.
- Ett spel avslutas och visar ett resultat på vinst, förlust eller oavgjort.
- En spelare kan skapa en spel inbjudan för att spela med sina vänner.
- En spel inbjudan leder till en match.
- En spelare kan välja svårighetsgrad mot dator.

```mermaid
classDiagram
    class Spelare
    class Spel
    class Spelplan
    class Position
    class Sten
    class Drag
    class Tur
    class Match
    class Resultat
    class Spelinbjudan
    class Svarighetsgrad

    Spelare "2" --> "1" Spel : deltar i
    Spel "1" --> "1" Spelplan : har
    Spelplan "1" --> "*" Position : bestar av
    Position "0..1" --> "1" Sten : innehaller

    Spelare "1" --> "*" Drag : gor
    Drag "1" --> "1" Sten : placerar
    Drag "1" --> "1" Position : pa

    Match "1" --> "*" Tur : har
    Tur "*" --> "1" Spelare : tillhor

    Match "1" --> "1" Resultat : har

    Spelare "1" --> "*" Spelinbjudan : skapar
    Spelinbjudan "1" --> "1" Match : leder till

    Spelare "1" --> "1" Svarighetsgrad : valjer
```
