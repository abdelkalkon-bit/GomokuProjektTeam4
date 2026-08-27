# GiomokuProjektTeam4
Det här repositoryt innehåller mitt skolprojekt. Projektet är skapat som en del av min utbildning och används för att visa mina kunskaper inom programmering och utveckling.  Här finns projektets källkod, filer och dokumentation. Syftet med projektet är att lära mig mer om utvecklingsprocessen

# Quyen_edit

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

## Projektstruktur

```
gomoku/
├── .gitignore                      # Filer och mappar som Git ska ignorera
├── README.md                       # Projektöversikt
├── LICENSE                         # Licens (om tillämpligt)
├── docs/                           # All projektdokumentation
│   ├── requirements/                # Kravfångst och kravdokumentation
│   │   ├── 01-inledning.md
│   │   ├── 02-funktionella-krav.md
│   │   ├── 03-kompletterande-krav.md
│   │   ├── 04-icke-funktionella-krav.md
│   │   ├── 05-begreppsmodell.md
│   │   ├── 06-user-journey.md
│   │   ├── 07-use-cases-overview.md
│   │   ├── use-cases/                # Enskilda Use Cases
│   │   │   ├── UC-01-starta-nytt-parti.md
│   │   │   ├── UC-02-gor-ett-drag.md
│   │   │   ├── UC-03-bjuda-in-van.md
│   │   │   └── ...
│   │   ├── 08-use-cases-och-test-cases.md
│   │   ├── 09-journal.md             # Journal – dagliga anteckningar
│   │   └── 10-reflektioner.md
│   └── diagrams/                    # Diagram (bilder, exportfiler m.m.)
│       ├── uml/                      # UML-diagram
│       ├── journey/                  # User Journey-diagram
│       └── readme.md                 # Information om dokumentationen
├── src/                             # Källkod (tom i detta skede)
├── tests/                           # Tester (tom i detta skede)
├── .github/
│   └── workflows/
│       └── ci.yml                   # CI-pipeline (exempel)
└── assets/                          # Resurser (bilder, ikoner, m.m.)
```

## Dokumentation

All kravdokumentation finns under [`docs/requirements/`](docs/requirements):

| Dokument | Beskrivning |
|---|---|
| `01-inledning.md` | Inledning till projektet |
| `02-funktionella-krav.md` | Funktionella krav |
| `03-kompletterande-krav.md` | Kompletterande krav |
| `04-icke-funktionella-krav.md` | Icke-funktionella krav |
| `05-begreppsmodell.md` | Begreppsmodell |
| `06-user-journey.md` | User Journey |
| `07-use-cases-overview.md` | Use Cases – översikt |
| `use-cases/UC-XX-*.md` | Enskilda Use Cases |
| `08-use-cases-och-test-cases.md` | Use Cases och Test Cases |
| `09-journal.md` | Journal – dagliga anteckningar |
| `10-reflektioner.md` | Reflektioner |

Diagram (UML, User Journey m.m.) finns under [`docs/diagrams/`](docs/diagrams).


