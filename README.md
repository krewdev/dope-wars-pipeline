# DOPE WARS: THE PIPELINE

Satirical 30-day trading game on Solana. Recipes are item IDs + a purity roll. No real chemistry.

## Play

Open `index.html` on your phone.

After Pages is enabled (`Settings → Pages → Source: GitHub Actions`):

https://krewdev.github.io/dope-wars-pipeline/

Until that click, github.io 404s. The HTML in this repo is the game.

### Day 1

FARM GREEN → JET QUEENS → MAP → join KIT ROW → buy CATALYST from LAB ROW → COOK GREEN + CATALYST → PAY HARRY.

## THE BLOCK (season 01)

Pokémon GO layer on top of the terminal.

- **MAP** — 6 city regions, 17 fictional beacons (wires + markets)
- **8 crews** — Greenhouse Kings, Kit Row, Suit Case, Yard Dogs, The Pit, Boardwalk Firm, Dock Union, Greenpoint Radio
- **SHARE FIX** — opt-in GPS. Hashes to a cell. Coordinates are not stored. Walk into a new cell = free snap, no day spent
- **RADIO** — deny GPS and the season still runs. Shadow borough for anyone outside the six books
- Flags + counts on the map. No player pins. Chat strips coordinates

This is a game. Beacons are preselected totems, not real corners. A wipe closes a claim PDA. It is not a real-world method.

## On-chain (skeleton)

- `programs/pipeline/src/constants.rs` — locked numbers
- `programs/pipeline/src/instructions/cook_commit.rs` — burn 8 strain + 2 kits + $50
- `programs/pipeline/src/instructions/cook_reveal.rs` — Cut vs Cert. Cert inits Token-2022 with PermanentDelegate = Cop PDA
- Next: Beacon / Faction / Claim / Heartbeat / RaidTicket

Harry is 10%/day. Vest of a certified cook locks 3 days.
