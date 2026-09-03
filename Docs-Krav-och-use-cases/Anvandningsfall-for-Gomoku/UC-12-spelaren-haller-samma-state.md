# Användningsfall 12 - Bevara Spelstatus

## Spelare vill fortsätta pausad match utan att spelbrädets tillstånd eller turordning förändras. 

| Fält          | Värden         |
|---------------|----------------|
| Use Case I2   | UC-12      |
| Namn          | Spelare vill fortsätta pausad match |
| Version       | 1.0        |
| Preliminär Aktör |En spelare|
| Sekundär Aktör | - |
| Relaterad FR | - |
| Relaterad NRF | -|

## Aktör:
En spelare.

## Mål:
Spelaren ska kunna fortsätta en pausad match utan att spelbrädets tillstånd eller turordning ändras.

### Förutsättningar:
- En match pågår
- Matchenb har ett aktuellt spelbräde och visar en turordning

# Huvudflöde
1. Spelaren gör ett giltigt drag på brädan
2. Systemet uppdaterar spelbrädet.
3. Systemet sparar den aktuella tillståndet.
4. Systemet behåller korret turordning
5. Nästa spelare kan göra sitt drag

# Förväntad resultat:

Spelbrädet och turordningen fortsätter att vara samma enligt senaste giltiga speltillstånd även efter uppdatering av spelbrädet. 
