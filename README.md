# GiomokuProjektTeam4
Det här repositoryt innehåller mitt skolprojekt. Projektet är skapat som en del av min utbildning och används för att visa mina kunskaper inom programmering och utveckling.  Här finns projektets källkod, filer och dokumentation. Syftet med projektet är att lära mig mer om utvecklingsprocessen

# Gomoku

Ett Gomoku-spel (fem i rad) utvecklat som del av kursinlämning. Detta repo innehåller all kravdokumentation, use cases och källkod för projektet.

## Innehåll

- [Om projektet](#om-projektet)
- [Projektstruktur](#projektstruktur)
- [Dokumentation](#dokumentation)
- [Kom igång](#kom-igång)
- [Testning](#testning)
- [CI/CD](#cicd)
- [Licens](#licens)

## Om projektet

Gomoku är ett strategispel för två spelare där målet är att få fem egna brickor i rad – horisontellt, vertikalt eller diagonalt – på ett rutnät.

Samtliga krav för systemet finns spårbara i detta Git-repo, som fungerar som gruppens gemensamma och versionshanterade kravdokumentation.



#  Projektstruktur

```text
gomoku/
├── .gitignore                         # Filer och mappar som Git ska ignorera
├── README.md                          # Projektöversikt/Dokumentation
├── LICENSE                            # Licens 
│
├── docs/                              # All projektdokumentation
│   ├── requirements/                  # Kravfångst och kravdokumentation
│   │   ├── 01-inledning.md            # Inledningen till hela projektet
│   │   ├── 02-funktionella-krav.md    # Funktionella krav för gomoku
│   │   ├── 03-kompletterande-krav.md  # Alla kompletterande krav finns här
│   │   ├── 04-icke-funktionella-krav.md # Icke-funktionella krav för gomoku
│   │   ├── 05-begreppsmodell.md       # Viktiga begrepp för gomoku och relationen mellan dom. 
│   │   ├── 06-user-journey.md         # hur en användare upplever och interagerar med systemet från början till slut.
│   │   ├── 07-use-cases-overview.md   //
│   │   │
│   │   ├── use-cases/                # Alla användningsfall 1-12
│   │   │   ├── UC-01-starta-nytt-parti.md 
│   │   │   ├── UC-02-gor-ett-drag.md
│   │   │   ├── UC-03-bjuda-in-van.md
│   │   │   └── ...
│   │   │
│   │   ├── 08-use-cases-och-test-cases.md
│   │   ├── 09-journal.md             # Journal – dagliga anteckningar
│   │   └── 10-reflektioner.md        # Reflektioner
│   │
│   └── diagrams/                     # Diagram och modeller
│       ├── uml/                      # UML-diagram
│       │   ├── 00-oversikt-Gomoku.md
│       │   ├── 01-sekvensdiagram-Gomoku.md
│       │   ├── 02-aktivitetsdiagram-Gomoku.md
│       │   └── 03-tillstandsdiagram-Gomoku.md
│       │
│       ├── journey/                  # User Journey-diagram
│       │   └── user-journey.md
│       │
│       └── readme.md                 # Inget här
│
├── src/                              //
│   └── ...
│
├── tests/                            //
│   └── ...
│
├── .github/                          //
│   └── workflows/                    //
│       └── ci.yml                    //
│
└── assets/                           //
    ├── images/                       //
    ├── icons/                        //
    └── ... 




