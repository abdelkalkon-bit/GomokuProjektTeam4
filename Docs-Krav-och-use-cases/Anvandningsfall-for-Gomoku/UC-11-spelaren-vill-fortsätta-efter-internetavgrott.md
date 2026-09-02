# UC-11-spelaren-vill-fortsätta-efter-internetavbrott

| Namn | Värde |
|-------|-------|
| User case ID | UC-11 |
| Namn på filen | Spelaren vill fortsätta efter internet avbrott |
| Version | 1.0 |
| Aktör | Spelare |
| Sekundär aktör | Ingen. |
| Relaterade FR | FR-08.1, FR-08.2 |
| Relaterade NRF | NFR-03, NFR-07, NFR-08 |

## Aktör:En spelare

## Mål: Spelaren vill återuppta en pågående match efter att ha förlorat internetuppkopplingen

## Förutsättningar:
* Spelaren hade en pågående match innan internetavbrottet
* Spelaren återfår internetuppkoppling
* Matchen är fortfarande aktiv (motståndaren har inte lämnat eller matchen avslutats)

# Huvudflöde:
1. Spelaren tappar internetuppkopplingen under en pågående match.
2. Systemet upptäcker att spelaren har blivit frånkopplad.
3. Systemet pausar matchen och väntar på att spelaren återansluter.
4. Spelaren återfår internetuppkoppling och öppnar spelet igen.
5. Systemet verifierar spelarens identitet innan återanslutning godkänns.
6. Systemet kopplar tillbaka spelaren till den pågående matchen.
7. Systemet visar spelplanen med senaste sparade tillstånd.
8. Matchen återupptas och spelet fortsätter från samma punkt som innan avbrottet.

## Alternativa flöden:
* 3a. Timeout: Om spelaren inte återansluter inom en viss tidsgräns, avslutar systemet matchen och motståndaren tilldelas vinst genom walkover.
* 5a. Misslyckad identitetsverifiering: Om systemet inte kan verifiera att det är rätt spelare som återansluter, nekas åtkomst till matchen och spelaren ombeds logga in på nytt.
* 6a. Motståndaren har lämnat matchen: Om motståndaren avbröt matchen under tiden spelaren var frånkopplad, meddelar systemet spelaren att matchen redan är avslutad och visar resultatet.
* 6b. Match mot dator: Om spelaren spelade mot datorn, återupptas matchen automatiskt utan väntetid eftersom motståndaren (datorn) inte påverkas av avbrottet.

# Förväntat resultat:
Spelaren återansluts säkert till sin pågående match och kan fortsätta spela från samma tillstånd som innan avbrottet. Om spelaren inte återansluter i tid, avslutas matchen och motståndaren vinner genom walkover.

Relevant GDPR-krav: Security Measures (Art. 32) – Systemet ska implementera lämpliga säkerhetsåtgärder, inklusive autentisering, för att säkerställa att endast rätt spelare kan återansluta till en pausad match.
