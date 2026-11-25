# NOTES — One Word for Your Wi-Fi

Competition: `u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72` — "One Word for Your Wi-Fi"
Sponsor: u-tuan-muda · Pot: $2 (1st takes all) · Harness: program/v1 · Entry fee: none (free)
Entries close: 28 Nov 2026 19:35 WITA · Submissions already: ~2,124 (checked 25 Nov 2026).
Blind rounds: 3 (final at the deadline).

## The task

The program writes one text to `/output/entry.txt`: exactly one word describing your Wi-Fi, 1 to 20 characters — the funniest and most accurate; the winning word becomes the sponsor's network name. The judge
reads entries two at a time against the published brief and picks the
funnier / stronger one. Copies: byte-identical entries share one rate,
with the earlier receipt placed above its copies — so a late copy of a
heavily copied line cannot take a paid place, and freshness of the pick
matters as much as the joke.

## The three variants

All three are complete standalone programs in `vA/`, `vB/`, `vC/`, each
writing its entry to `/output/entry.txt` with the same validate → write →
read-back → print structure. The root `main.ts` is the chosen variant.

### Variant vA — "Schrödinger" (CHOSEN, root `main.ts`)

The Wi-Fi is both connected and not connected until you observe it — which is exactly how home Wi-Fi behaves: full bars, no internet. It is funny at once, recognisably true, and a surprising angle on a familiar annoyance; a reader gets it instantly, and it works as a network name. Field check (25 Nov): 14 copies in the submissions list — far fewer than the obvious picks.

### Variant vB — "Elsewhere"

The Wi-Fi is always elsewhere: in the next room, at the neighbour's, anywhere but here. Ranked second: the image is true and fresh, but it is quieter than Schrödinger and needs half a second of thought.

### Variant vC — "Blinking"

The router lights blink, the connection blinks in and out — one word, true, visual. Ranked third: it describes the router more than the Wi-Fi experience, and the joke is thinner.

## Why vA was chosen

vA wins on the brief: it is one word describing Wi-Fi as lived (full bars, zero internet); it is funny at once — the quantum joke lands without explaining; it feels true to how home Wi-Fi actually behaves; it avoids the words everyone reaches for ('Ghosting' has 242 copies in the field, 'Moody' 28, 'Schrödinger' only 14); and it works as a single word with no context, spelled so a reader gets it instantly — and it would make a good network name.
