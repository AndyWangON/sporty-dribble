# Sporty Dribble — Anime Edition

A browser-playable prototype that preserves the original Sporty Dribble mechanics while upgrading the presentation to anime / cel-shaded rendered cinematic assets.

## Run
Open `index.html` in a modern browser. No npm, bundler, or CDN is required.

## Preserved game mechanics
- 3 dribble stages
- 2 or 3 defenders per stage
- Weak / Normal / Strong defender classes
- Route-specific odds using the original formulas
- 94% RTP probability model (`success probability = RTP / route odds`, clamped)
- 7 second decision timer
- Preview + reroll before starting
- Stake and cumulative multiplier
- Automatic goal after 3 successful dribbles

## Presentation upgrade
- Anime/cel-shaded rendered character art
- Defender portrait cards
- Animated route trails and timer HUD
- Multi-frame dribble success cinematics
- Multi-frame tackle/failure cinematics
- Multi-frame shot/goal cinematic
- Motion zoom, impact flash, particles, letterboxing and audio cues

## Production note
For real-money use, move RNG, odds settlement, stake validation and result signing to a trusted server. The browser should receive an authoritative result and only render the corresponding animation.
