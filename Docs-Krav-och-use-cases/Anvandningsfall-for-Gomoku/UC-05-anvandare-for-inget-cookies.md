# UC-05- Användaren hanterar cookies

| Namn | Värde |
|-------|-------|
| User case ID | UC-05 |
| Namn på filen | Användaren hanterar cookies |
| Version | 1.0 |
| Aktör | Spelare |
| Sekundär aktör | Ingen |
| Relaterade FR | FR-05.1,FR-05.2, FR-05.3, FR-05.4,FR-05.5 |
| Relaterade NRF | Användbarhet/ GDPR |

## GDPR relevant test: Cookie Consent och Privacy/Transparency.

Aktör: En spelare 

Mål: Användaren ska kunna hantera cookies när hen besöker Gomoku för första gången, spårning men även kunna fortsätta spela även om hen nekar cookies. 

Förutsättning: Användaren besöken hemsidan för Gomoku

### Huvudflöde:

1. Användaren öppnar webbplatsen för Gomoku
2. Systemet informerar användaren om det finns cookies eller annan typ av spårning som används.
3. Användaren kan både accpetera eller neeka det som kräver godkännande. 
4. Systemet ser till att den sparar användarens val.
5. Spelet fortsätter att fungera som den ska utan att spelaren behöver godkänna cookies.

### Alternativa flöde: 
-  Användaren nekar cookies
- Systemet applicerar användarens val och använder inte cookies som kräver samtycke. 

### Förväntat resultat av denna GDPR-test: 

Kontrollera att cookies eller annan typ av spårning inte goodkänns automatiskt utan samtycke. Användaren får information om användingen av cookieis på hemsidan och hantera acceptera eller neka dom. Gomoku ska även fortfarande vara möjlig att spela även när cookies nekas.  
