# Användningsfall - Gomoku 
## UC-01 Starta en match i Gomoku


| Fält | Värden |
|-------|-------|
| **Use Case ID** | UC-01 |
| **Namn** | Starta en match i Gomoku |
| **Version** | 1.0 |
| **Prelimär Aktör** | Gäst User, Registerad spelare |
| **Sekendära Aktör** | AI Motståndare |
| **Relaterad FR** | FR-01.1, FR-01.2, FR-01.3, FR-01.4, FR-01.5 |
| **Relaterad NFR** | NFR-01: Användarvänlighet, NFR-03: Prestanda |

Aktör: En spelare

Mål: Spelare vill starta ett nytt Gomoku match

Förutsättningar:

- Spelaren har internet 
- Spelaren befinner sig på spelets startsida

### Huvudflöde:

 1. Spelaren väljer att starta ett nytt spel och får upp att spela mot någon eller mot dator.
 2. Systemet skapar en ny match för spelaren efter sitt beslut.
 3. Systemet visar spelplanen för spelaren.
 4. Systemet anger automatiskt vilken spelare som börjar.

### Förävntat resultat:
En ny match har startats med rätt motståndartyp (dator eller människa). Spelplanen är tom och redo för första motståndare att göra ett drag. Turordningen har även aktiverts för den spelare som ska börja.

