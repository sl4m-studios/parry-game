# PARRY!

One button. Sixty seconds. All timing.

A single-file HTML5 fighting game prototype. Tap the instant before your rival strikes to parry. String 3 parries for a SUPER. Best in short bursts on mobile.

## Play

Open `index.html` in any modern browser, or visit the GitHub Pages link.

## Modes

- **Tutorial** — guided 4-step intro (no damage, slow pace)
- **VS AI** — practice against ramping AI difficulty
- **VS Player** — real online P2P matches via WebRTC (PeerJS broker, no backend required)

Online uses a simple lobby pattern: two players who hit "VS PLAYER" within 14 seconds get matched.

## Ranked

Online matches are ranked. Wins +25 RP, losses -12 RP. Tiers: Bronze → Silver → Gold → Platinum → Diamond → Champion → Apex (each with 3 divisions).

## Controls

- Tap anywhere on screen (or press Space) to parry
- One button — that's it

## Tech

- Single `index.html`, zero build step
- HTML5 Canvas for rendering
- Web Audio API (synthesized sounds, no asset files)
- PeerJS for P2P matchmaking
- localStorage for rank, stats, settings
