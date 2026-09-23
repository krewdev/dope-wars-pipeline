# 14  /  THE BLOCK
Season 01 layer. Cities stay regions. Does not replace JET, Harry, coat, or cook→mint.

## Names
| HUD | PDA | PoGO analog |
|---|---|---|
| CREW | Faction | team |
| CARTEL | Faction holding ≥3 MARKETS | gym stack |
| CELL | Beacon you occupy | current stop |
| SHOES / WIRE | Beacon kind=SHOE | PokéStop |
| MARKET / CORNER | Beacon kind=CORNER | Gym |
| CLAIM | Claim | gym control |
| RADIO | no Heartbeat | play without GPS |

## Crews (season 01 stub)
| ID | Name | City | Specialty |
|---|---|---|---|
| KINGS | GREENHOUSE KINGS | Brooklyn | GREEN |
| ROW | KIT ROW | Queens | CATALYST |
| SUITS | SUIT CASE | Manhattan | BURN |
| YARD | YARD DOGS | Bronx | CUT |
| PIT | THE PIT | Coney | BURN |
| FIRM | BOARDWALK FIRM | Coney | GLAZE |
| DOCK | DOCK UNION | Bridgeport | BINDER |
| RADIO | GREENPOINT RADIO | Shadow / Brooklyn | DUST |

PURP / FROST / DANK / GLASS stay farmed or spun — not stall-locked.

## Beacons
Fictional game nodes only. No real corners. No player-dropped pins.

Wires: THE GREEN WIRE, RADIO MAST, BENCH ON THE 7, TICKER STEPS, VAULT STEPS, YARD LINE, BOARDWALK WIRE, DOCK BELL, LOCKER WIRE
Markets: LOT SEVEN (KINGS), LAB ROW (ROW), TWO-KIT ALLEY (unheld), BILLBOARD PIT (SUITS), THIN BOOK (YARD), THE PIT RAIL (PIT), SHOE CARNIVAL (FIRM), EXIT STALL (DOCK)

## GPS
- SHARE FIX opt-in. Deny = RADIO.
- watchPosition / getCurrentPosition → hashed cell only. Never store raw lat/lon.
- Same cell always maps to the same shadow beacon.
- Cell change = walk into a new cell, free snap, 0 day.
- Outside the six books, FIX maps to RADIO MAST / GREENPOINT RADIO.
- Map shows crew flags + a count. No player pins.

## Economy
NPC vendors 1.4×. Your-crew stall 0.85×. Enemy stall refused 2.2×.
Holder cut on SELL/BURN: 8%.
Spin: 5 min if FIX live; 1 act in RADIO; 3rd same shoe same day = dust.
Drip ticks (this build): RURAL 8 / STRIP 22 / METRO 55 / LANDMARK 90
payout *= (1 + 0.08 * teammates_present), cap 5
Buy-off = 3× last drip tick.
Wipe = 1 certified slot OR 1 SHOT. Node UNHELD until tomorrow.

## Chat
AREA / CREW / COLLAB. Strip coords and "meet me at". Nicknames only.

## On-chain later
Beacon, Faction, Claim, Heartbeat (15 min TTL, coarse geohash), RaidTicket.
