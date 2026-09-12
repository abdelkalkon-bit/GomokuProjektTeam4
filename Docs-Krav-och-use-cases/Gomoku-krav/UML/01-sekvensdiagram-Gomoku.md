# Sekvensdiagram för gomoku

#### Man utgår från centrala flödet genom att spelare gör först ett drag > Systemet validerar > brädet uppdateras > spelet kontrollerar om det blev vinst eller oavgjort > nästa spelare ifall ingen har vunnit. 


```mermaid
sequenceDiagram
    actor Spelare
    participant Spel as Spel
    participant Brade as Spelbräde
    participant Kontroll as Spellogik

    Spelare->>Spel: Gör ett drag (rad, kolumn)
    Spel->>Brade: Kontrollera om platsen är ledig
    Brade-->>Spel: Platsen är ledig

    Spel->>Brade: Placera spelpjäs
    Brade-->>Spel: Brädet uppdaterat

    Spel->>Kontroll: Kontrollera vinst
    Kontroll-->>Spel: Ingen vinnare

    Spel->>Kontroll: Kontrollera oavgjort
    Kontroll-->>Spel: Spelet fortsätter

    Spel->>Spel: Byt spelare
    Spel-->>Spelare: Visa uppdaterat bräde
```
