# Business Rules för Gomnoku
Nedan finns regler och villkor som systemet alltid ska följa under en Gomoku match. Reglerna gäller oavsett om spelaren spelar mot en dator, lokalt eller mot en annan spelare eller på distans. 

## Match och spelare regler:

| ID | Regler |
|-------|-------|
|BR-01|En Gomoku match ska alltid bestå av två motståndare. Motståndaren kan vara en riktig person eller en dator.|
|BR-02|En spelare ska kunna starta en match utan att behöva skapa ett konto eller logga in (Spela som gäst) |
|BR-03|En spelare ska kunna delta i en match utan att behöva lämna sina personuppgifter för att spela. |
|BR-04|En match ska alltid ha ett tydlig spelläge, mot daotr eller lokalt-spel eller distans.|
|BR-05|En pågående gomoku match ska ha ett tillstånd som visar spelbräde, placerade stenar och vilken spelares tur det är|

## Spelbräde och position regler
| ID | Regler |
|-------|-------|
|BR-6|Ett drag får endast place en sten från sin plats till en ledig position|
|BR-7|En position som är upptagen får inte användas för ett nytt drag|
|BR-8|Ett drag kan bara utföras på en position som finns på spelbrädet|
|BR-9|En sten kan inte flyttas efter att den har placerats på en ledig position|
|BR-10|Varje drag ändrar matchens aktuella tillstånd tills någon vinner|
|BR-11|Brädans tillstånd ska vara konsekvent för båda spelarna i en match som sker på distans.|

## Turordningen regler
| ID | Regler |
|-------|-------|
|BR-12|Endast när det är spelarens tur som hen får göra ett drag|
|BR-13|Spelarna ska alltid turas om att göra ett drag |
|BR-14|När ett giltigt drag blir gjort så¨ska turen alltid gå vidaren till motståndaren, om matchen inte har avslutats. |
|BR-15|Ett ogiltigt drag av en spelare får inte ändra turordningen|
|BR-16|Systemet ska alltid kunna hantera vems tur som är aktuell. |

## Vinst, förlust och oavgjort
| ID | Regler |
|-------|-------|
|BR-17|En spelare vinner matchen när hen får fem egna stenar i rad horisontellt, vertikalt eller diagonalt|
|BR-18|När en spelare får fem i rad avslutas matchen direkt. Motståndaren förlorar mot den som får fem i rad|
|BR-19|Om hela spelbrädet blir fullt innan någon spelare får fem i rad blir matchen oavgjord |
|BR-20|När en match avslutas genom vinst eller oavgjort får intga fler drag göras i matchen|

## Regler för-Spela mot datorn 
| ID | Regler |
|-------|-------|
|BR-21|När en spelare kör mot dator ska matchen fungera precis som en motståndare och endast göra drag när det är datorns tur|
|BR-22|Spelaren ska kunna välja innan matchen vilken svårighetsgrad hen vill ha. Lätt, medel eller svår|
|BR-23|Datan ska alltid följa grundläggande spelregler precis som en mänsklig spelare|

## Lokalt spel och distans-regler
| ID | Regler |
|-------|-------|
|BR-24|Vid lokalt spel så spelar två personer från sammma enhet och turas om att göra drag tills någon vinner|
|BR-25|Vid distansspel ska två spelare kunna spela samma match från olika platser via internet|
|BR-26|En spellänk ska kunna skapas av en seplare som hen kan dela med motståndaren|
|BR-27|En spelare ska kunna ansluta till en distans match via spellänken utan att behöva ha ett konto eller logga in|
|BR-28|Spelarna i en distansmatch ska kunna dela samma spelbräde, turordning och resultat|
## Pausa och återuppta en match 
| ID | Regler |
|-------|-------|
|BR-29|En pågående match ska kunna pausas vid behov utan att aktuella tillstånd på spelbrädet och turordningen förloras.|
|BR-30|När en pausad match återupptas så ska den alltid fortsätta från samma tillstånd som innan den pausades|
|BR-31|En avslutad match ska inte kunna återupptas som en pågående match|

## Internetavbrott 
| ID | Regler |
|-------|-------|
|BR-32|En tillfällig internetavbrott ska inte automatiskt avsluta en pågående match som sker på distans mellan två spelare|
|BR-33|När seplaren återansluter ska systemet alltid återställa den senaste giltiga spelstatus, tillstånd och turordning. (Om motståndaren inte har valt att avsluta matchen) |

## Anonymt spelande 
| ID | Regler |
|-------|-------|
|BR-34|En Gomoku match ska kunna spelas anonymt utan att användaren behöver skapa ett konto eller logga in|
|BR-35|Spelet ska alltid kunna användas direkt i en webbläsare utan att spelaren behöver installera något program|
|BR-36|Spelet ska kunna användas på både datorer och mobiltelefoner|

