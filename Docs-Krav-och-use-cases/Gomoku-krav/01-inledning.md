# Inledning för projeket
Projektet handlar om att utveckla ett spel som är webbaserad där en användare kan spela direkt i webbläsaren.
Spelet heter Gomoku och tanken är att det ska vara enkelt att komma igång och börja spela utan att användaren ska behöva installera något program eller skapa ett konto.

# Syftet med systemet

Syftet med systemet/spelet är att skapa ett enkelt Gomoku-spel där en användare ska kunna vinna, förlora eller att det blir oavgjort. Mycket fokus ligger på att få spelet att fungera på ett smidigt sätt för nya spelare samt att det ska vara lätt att förstå hur man spelar enligt regler. 

Det ska även gå att spela mot en dator eller mot en annan person. Om två personer vill köra mot varandra och använder samma enhet, så ska det kunna gå att spela mot varandra. Det finns även en möjlighet att spela mot någon på distans genom att dela en länk med personen till spelet. 

# Användare?

Systemet är huvudsakligen skapat framäst för personer som vill spela Gomoku utan att behöva stöta på krångliga inställingar som tar onödigt mycket tid. Användaren ska alltså kunna öppna spelet i en webbläsare och börja spela direkt utan hinder. 

Applikationen fungerar även på olika typer av enheter, som till exempel mobiltelefoner och datorer. En person som blir inbjuden till ett spel ska kunna ansluta till matchen och börja spela direkt utan att behöva skapa ett konto eller installera någon program eller applikation.

# Finns det problem som systemet ska lösa?

många spel idag kräver en registrering eller installation innan man börjar spela en match. Ett av problemen som systemet ska lösa är att göra det enklare att spela Gomoku utan att användaren behöver installera något eller att ett konto skapas. Målet är att användaren ska kunna starta ett spel och välja om den vill spela mot datorn eller mot en annan person utan krångel eller krav på installation eller konto. 

Systemet ska därför vara enkelt att använda när två personer spelar mot varandra på samma enhet eller när de spelar på distans genom en länk. Samtidigt behöver spelet även reagera snabbt på användarens handlingar för att spelupplevelsen ska kännas smidig för båda spelarna och inte onödigt långsam. 

# Översikt över dokument strukturen
| Namn på fil | vad finns i den? | 
|------|------:|
| Begreppslista-00 | En mapp med en fil som innehåller alla domän och tekniska termer som anävnds i kravspecifikationen |
| 01-inledning.md | System beskrivning med syftet, användare och problem som ska de ska lösa |
| 02-funktionella-krav.md | Tabeller över nödvändiga krav för vad systemet måste kunna göra |
| 03-kompletterande-krav.md | Extra villkor och lagkrav som måste uppfyllas för att ett system ska fungera fullt ut. |
| 04-icke-funktionella-krav.md | Krav på systemet som är viktiga för användarupplevelse. Prestanda/ användbarhet/  kompatibilitet/tillförlitlighet |
| 05-begreppsmodell.md | Viktiga centrala begrepp i systemet och vad dom har för relation till systemts funktion |
| 06-user-journey.md | Beskrivning på hur en användare upplever och interagerar med systemet från början till slut när användaren försöker att uppnå ett specifikt mål i systemet. |
| 07-use-cases-overview.md | INGEN ÄN | 
| 11-business rules| Villkor, formler och strategier som bestämmer hur en verksamhet fungerar och vad systemet måste följa |
| 12-traceability-matrix.md | Koppla samman och spåra krav mot design, kod och testfall |

# Översikt över användningsfall för Gomoku 
| Namn på fil | vad finns i den? |
|------|------:|
| UC-01-starta-en-match.md | UC för en spelare som vill starta ett nytt Gomoku |
| Uc-02-spela-mot-en-dator.md | UC för en spelare som vill spela en Gomoku match mot en dator |
| UC-03-valja-svarighetsgrad.md | UC för en spelare som väljer svårighetsgrad mot en dator |
| UC-04-användaren spelar anonymt-utan-konto | UC för en spelare som använder Gomoku för första gången (GDPR) |
| UC-05-anvandare-for-inget-cookies.md | UC för en spelare som hanterar cookies (GDPR) |
| UC-06-anvandare-bjuder-in-med-lank | UC för en spelare som bjuder sin vän med en länk |
| UC-07-spelaren-ansluta-till-en-match.md | UC för en spelare som försöker återansluta till en match |
| UC-08-spelaren-vill-avsluta-match.md | UC för en spelare som vill avsluta en pågående match |
| UC-09-spelaren-vill-forsatta-pagaende-match.md | UC för en spelare som fortsätta en pågående match |
| UC-10-spelaren-vill-se-match-resultat.md | UC för en spelare som vill se resultatet av en match |
| UC-11-spelaren-vill-fortsätta-efter-internetavbrott.md | UC för en spelare som vill fortsätta en match efter internetavbrott |
| UC-12-Spelaren-håller-samma-state | Inget än |



