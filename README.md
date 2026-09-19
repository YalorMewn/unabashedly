# Unabashedly — design files

Everything the brand runs on, in one place. Last updated 2026-09-19.

**Brand:** Unabashedly — "Coaching with Taylor Arnold"
**Domain:** unabashedly.dad (registered at Namecheap)
**Instagram:** [@unabashedlydaddy](https://www.instagram.com/unabashedlydaddy/)

## What's in here

| Path | What it is |
|---|---|
| `brand/style-guide.html` | The Brutalist Grid style guide v1.0 — color, type, spacing, components, imagery, voice, do/don't. Open it in a browser. |
| `brand/tokens.css` | The style guide turned into usable CSS: every color, font and spacing value, plus the button, card and icon styles. Drop it into any new page. |
| `photos/taylor-portrait-880x1100.jpg` | The cropped portrait used on the site. Black and white is applied by CSS, so this file is still in color. |
| `photos/source/taylor-grey-tee.jpg` | Full-size original of the portrait above. |
| `photos/source/taylor-mountain.jpg` | Full-size alternate (mountain, shirtless). Not used — eyes closed, busy background. |
| `site-snapshot/` | Copy of the two live pages as of 2026-09-19, for reference only. Don't edit these. |

**The editable site lives in its own folder:** `~/taylor-coaching-site` (a separate git repo). That's the one that gets published. The copies in `site-snapshot/` are just so the design files are complete on their own.

## The design in short

**Color** — flat only. No gradients, no tints, no drop shadows.

| Name | Hex | Used for |
|---|---|---|
| Paper | `#F1EEE7` | The page background |
| Paper 2 | `#E7E1D2` | Panels, hover states |
| Ink | `#0E0D0C` | Text, borders, rules |
| Ink 70 | `#54514A` | Secondary text and captions |
| Yellow | `#F4C61E` | Main buttons |
| Red | `#E64327` | One emphasis per page. Never in the same block as yellow. |

**Type** — three fonts, three jobs, all free from Google Fonts.
- **Anton** — headlines and big numbers. Uppercase, 32px and larger.
- **Space Grotesk** — everything people read: body text, buttons, navigation.
- **Space Mono** — anything that behaves like data: labels, durations, tags.

**Structure** — thick black borders doing real work, sharp corners on panels and cards, rounded only where something is clickable. Photos are black and white with hard edges.

**Voice** — short, declarative, second person. Statements, not questions. Every headline should survive being read out loud in one breath.

## The pages

**Home** (`index.html`) — the link page for your Instagram bio: Clarity Call (yellow, featured), Own The Outcome, Dad Club, then Who this is for / Ways to work with me, and the "Not ready?" link.

**Ways to work with me** (`work-with-me.html`) — headline, portrait, and stacked buttons at the top; then Who this is for, the three offers as rows, and the free-PDF email box.

## Links used on the site

- **Clarity Call booking:** https://app.reclaim.ai/m/taylor-cmprssn/clarity-call
- **Dad Club (Skool):** https://www.skool.com/dad-club-8098/about
- **Instagram:** https://www.instagram.com/unabashedlydaddy/

## Still open

- **GitHub repo** `yalormewn.github.io` hasn't been created yet, so nothing is published.
- **DNS** at Namecheap still points unabashedly.dad at a placeholder page.
- **The email box** says "Preview only" until an email tool is connected and the PDF exists.
- **Own The Outcome** has no link of its own; its button books a Clarity Call instead.
- **Naming:** the Dad Club row says "Dad Club" while two other spots still say "The Unfiltered Dad Club".
- **Dad School:** decide whether it's retired or becomes a program under Unabashedly.
