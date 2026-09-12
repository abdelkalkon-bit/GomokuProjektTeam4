# Tillståndsdiagram - Gomoku

Här fokuserar vi mer på spelets livscykel, alltså inte varje intern metod utan bara olika tillstånd som systemet kan befinna sig som går att verifiera genom olika testfall.


```mermaid
stateDiagram-v2
    [*] --> VäntarPåStart

    VäntarPåStart --> Pågående: Starta Gomoku-spel

    Pågående --> KontrolleraDrag: Spelaren väljer ruta

    KontrolleraDrag --> Pågående: Ogiltig ruta
    KontrolleraDrag --> DragGenomfört: Giltig ruta

    DragGenomfört --> KontrolleraVinst: Spelpjäs placerad

    KontrolleraVinst --> Vinst: Fem i rad
    KontrolleraVinst --> KontrolleraFulltBräde: Ingen vinnare

    KontrolleraFulltBräde --> Oavgjort: Spelbrädet är fullt
    KontrolleraFulltBräde --> Pågående: Spelbrädet är inte fullt

    Vinst --> VäntarPåStart: Starta nytt spel
    Oavgjort --> VäntarPåStart: Starta nytt spel

    VäntarPåStart --> [*]: Avsluta
```
