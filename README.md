# Dev Toolkit Plugin

Een handige Claude Code plugin voor ontwikkelaars die hun code sneller willen reviewen en wijzigingen willen documenteren.

## Wat doet deze plugin?

De Dev Toolkit plugin voegt twee powerful tools aan Claude Code toe:

### Commands (Slash Commands)

- **`/dev-toolkit:summarize-changes`** — Vat alle wijzigingen op de huidige branch samen met een regel per bestand. Perfect voor het snel opvullen van pull-request beschrijvingen.

### Agents (Subagents)

- **`code-reviewer`** — Een gespecialiseerde agent die je recente code wijzigingen analyseert op bugs, ontbrekende foutafhandeling en onduidelijke naamgeving. Handig direct na het schrijven of wijzigen van code.

## Hoe te gebruiken

### De samenvatting-command gebruiken

Voer `/dev-toolkit:summarize-changes` uit in Claude Code om een snelle samenvatting van wijzigingen op je huidige branch te krijgen.

### De code-reviewer agent gebruiken

Vraag Claude om je recente wijzigingen te beoordelen — de agent zal automatisch de code-reviewer agent gebruiken en je feedback geven gegroepeerd op ernst (hoog, medium, laag).

## Vereisten

- Claude Code
- Git repository

## Versie

v0.1.0
