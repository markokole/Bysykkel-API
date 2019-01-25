### Om løsningen
Jupyter notebook med Python 3 gjør 2 API spørringer mot `https://oslobysykkel.no/api/v1` og henter json objekt med informasjon om alle bysykkel stasjoner og json objekt med status på alle stasjonene (antall ledige plasser og antall sykler).

### Prereq
1. Installert Jupyter med Python 3.
2. `Identifier` for å kunne kjøre spørringer mot url-en.

### Hvordan å teste
Når du er i selve Jupyter notebook med navn `Bysykkel Availability via API.ipynb` må du først skrive `identifier` i første cellen og deretter kjøre notebook-en på følgende måte: `Kernel` -> `Restart & Run All`.
Siste cellen bør skrive ut en tabell med stasjon navn, antall ledige sykler og antall ledige plasser. 
