# Candleguard Design Bible

![Candleguard cinematic key art](04_Concept_Art/Champions/2026-09-12_Candleguard_README_Hero_v04.png)

Candleguard is a competitive hero action game set in the endless underground kingdoms of the kobolds.

Players control named kobold champions in a single-lane PvP push built for 1v1, 2v2, and 3v3 matches. The world is full of mining crews, tunnel beasts, scavenger contraptions, ritual candles, dangerous Shinies, and things in the Deep that kobolds only half-understand.

The core fantasy is simple: tiny, overconfident tunnel engineers with candles on their gear march into impossible darkness and somehow make it everyone else's problem.

## Current Identity

- Working title: Candleguard
- Genre: competitive hero action / single-lane PvP push
- Primary characters: unique named kobold champions
- Setting: subterranean kobold kingdoms expanding through tunnels, mines, ruins, and unstable depths
- Tone: funny at the surface, threatening in play, with an eerie mythic layer underneath
- Visual direction: saturated colors, overblown proportions, readable top-down silhouettes, realistic material rendering over cartoony shapes

## Repository Map

- `00_Vision/` - game vision, pillars, and art direction
- `01_World/` - lore, factions, terminology, and setting rules
- `02_Gameplay/` - loop, lanes, economy, creeps, and objectives
- `03_Champions/` - champion principles and individual champion concepts
- `04_Concept_Art/` - generated art, references, style studies, and image notes
- `05_Decisions/` - decision log and open questions
- `Archive/` - old directions, retired ideas, and historical notes

## Concept Art Naming

Use descriptive filenames so the art remains searchable:

```text
YYYY-MM-DD_Category_Subject_v01.png
```

Examples:

```text
2026-09-12_Candleguard_Champion_StyleStudy_v01.png
2026-09-12_RatScavenger_CandleVariant_v01.png
2026-09-12_MoleBruiser_CandleVariant_v01.png
2026-09-12_Lane_Layout_v03.png
```

Images should live in the most relevant folder under `04_Concept_Art/`. Large image files are tracked through Git LFS.

## Working Practice

This repository is the source of truth for design intent. When the Unreal project needs implementation guidance, start here first, then update this bible when decisions change.
