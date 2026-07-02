# Dispatch

Dispatch er en lokal-først macOS-app for å fange, organisere og sende ut **prompts og to-dos** på tvers av alle AI-/kodeprosjektene dine. Den erstatter en rotete Apple Notes-arbeidsflyt med ett samlet, strukturert sted — bygget for å stå smalt ved siden av nettleseren i split-screen.

Dette repoet inneholder **kun app-filene og auto-update-feeden** — ingen kildekode og ingen data.

## Last ned

Nyeste versjon: **[Releases](https://github.com/viavicdev/dispatch-releases/releases/latest)** → last ned `Dispatch-<versjon>-arm64.dmg` → åpne og dra `Dispatch` til Programmer.

Appen er **signert + notarisert** (Apple Developer ID), så den åpner uten Gatekeeper-advarsel. Etter første installasjon **oppdaterer den seg selv** (viser en «Oppdater nå»-banner når ny versjon finnes).

## Hva den gjør

- **To vinduer.** Et romslig **hovedvindu** for oversikt og planlegging, og et smalt **sidecar**-vindu for hurtig fangst ved siden av Chrome. De er live-synket — endring ett sted dukker opp det andre med en gang.
- **Prompts/to-dos som kort**, sortert etter prosjekt, med **binær status** (gjort / ikke gjort via avkryssing). Ingenting forsvinner.
- **Paraplyer** (prosjektgrupper) og valgfrie **tema/under-kategorier** som underoverskrifter.
- **Dashbord** med fremdrift per prosjekt, søk og filtre.
- **Prosjekt-oppsett**: farger, logoer, paraplyer, skjul/vis prosjekter.
- **Sidecar**: fangst-linje, «skriv-i-prosjekt»-modus for lange prompts, paraply-faner, innstillinger.

## Data & personvern

100 % lokalt. Alt lagres lesbart i `~/_SYNCED/Dispatch/dispatch-board.json` på din egen maskin. Ingen sky, ingen kontoer, ingen server. Legg fila i en synket mappe (Resilio/iCloud/Dropbox) for å dele samme data mellom flere Mac-er — appen overvåker fila og oppdaterer live når den endres et annet sted.
