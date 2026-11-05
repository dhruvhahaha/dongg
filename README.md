# Dongg

A tiny dong → rupee converter for the Vietnam trip.

**The rule:** drop the last three zeros, then multiply by 4.
`100.000 ₫ → 100 × 4 = ₹400`

## What it does

- Type a price (`100000`, `100.000`, `100k`, `1.5tr`, `1tr5` all work). The `000` key adds three zeros on a phone keypad.
- Shows the rupee amount big, plus the working and what the real rate would say.
- Tap banknotes (1k to 500k) to add up cash in hand.
- Flip to ₹ → ₫ to see how much dong a rupee budget gets you.
- Spend log with a running total, saved on each phone.
- Street price cheat sheet (phở, bánh mì, Grab bike, etc.).
- The rule is fixed at ×4 so everyone's numbers match. ×4 is about 9% above the real rate (₹1 ≈ 273 ₫, late Oct 2026), which makes a safe buffer.
- Installable to the home screen and works offline once loaded.

## Hosting on GitHub Pages

Repo **Settings → Pages → Build and deployment → Deploy from a branch → `main` / root**.
The site appears at `https://<username>.github.io/dongg/`. Open it on your phone and use *Add to Home Screen*.
