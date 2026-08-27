# UC-05- Användaren hanterar cookies

| Namn | Värde |
|-------|-------|
| User case ID | UC-05 |
| Namn på filen | Användaren hanterar cookies |
| Aktör | guest spelare|  
| Relaterade NRF | Användbarhet GDPR |

## GDPR relevant test: Cookie Consent och Privacy/Transparency.

Aktör: En spelare 

Mål: Systemet fungerar trots att användaren inte godkänner cookies. Systemet accepterar även inte cookies automatiskt utan användarens godkännande. 

Förutsättning: Användaren besöken hemsidan för Gomoku

### Huvudflöde:

1. Användaren öppnar webbplatsen för Gomoku
2. Systemet informerar användaren om det finns cookies eller annan typ av spräning som används.
3. Användaren kan både accpetera eller neeka sådant som kräver godkännande. 
4. Spelet fortsätter att fungera som den ska utan att spelaren behöver godkänna cookies.

### Förväntat resultat av denna GDPR-test: 

Kontrollera att cookies inte accepteras automatiskt utan användarens godkännande. 
