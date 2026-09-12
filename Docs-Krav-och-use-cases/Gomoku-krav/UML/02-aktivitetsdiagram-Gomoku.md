# Aktivitetsdiagram för gomoku

#### Här är det viktigt att visa både ogiliga och giltiga drag men även vinst,oavgjort och nästa tur. 
#### Use case > testfall: verifierar att systemets funktion uppfyller kravet/scenariot som finns i dem olika UC.
#### Aktivitetsdiagram > testfall: Hjälpte oss hitta flöden/alternativa vägar och edge cases som kanske inte är tydliga i våra UC

```mermaid
flowchart TD
    A([Start]) --> B[Starta spel]
    B --> C[Visa spelplan]
    C --> D[Spelare väljer ruta]

    D --> E{Är rutan ledig?}

    E -- Nej --> F[Visa felmeddelande]
    F --> D

    E -- Ja --> G[Placera spelpjäs]
    G --> H{Finns fem i rad?}

    H -- Ja --> I[Visa vinnare]
    I --> J([Spelet avslutas])

    H -- Nej --> K{Är spelplanen full?}

    K -- Ja --> L[Visa oavgjort]
    L --> J

    K -- Nej --> M[Byt spelare]
    M --> C
```
