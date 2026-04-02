# CHANGELOG — Caeseysolutions/drivealert
# File: CHANGELOG.md
# Repo: https://github.com/Caeseysolutions/drivealert
# Live URL: https://drivealert.eu

---

## VERSION REGISTRY

| Version | Date | File deployed | Commit message | Deployed by |
|---|---|---|---|---|
| v6 | 2 Apr 2026 | index.html | drivealert index v6 - full multilingual fix EN/NL/FR/DE | Kristof |
| v5 | 2 Apr 2026 | index.html | drivealert index v5 - button text + hero The fix | Kristof |
| v4 | 2 Apr 2026 | index.html | drivealert index v4 - dashcam + markets translations | Kristof |
| v3 | 2 Apr 2026 | index.html | drivealert index v3 - Three tools + images + NL bleed fix | Kristof |
| v2 | 2 Apr 2026 | index.html | drivealert index v2 - Three tools meta + product images | Kristof |
| v1 | Mar 2026 | index.html | Initial deploy - geo-routing + multilingual | Kristof |

---

## v6 — 2 April 2026
**File:** index.html
**Commit message:** `drivealert index v6 - full multilingual fix EN/NL/FR/DE`
**Keys per language:** 185

### What changed
- Fix: "✓ Germany — E1 Approved" now translated all 4 languages
  - FR → ✓ Allemagne — Homologué E1
  - NL → ✓ Duitsland — E1 Goedgekeurd
  - DE → ✓ Deutschland — E1 Zugelassen
- Fix: "Check current price →" (P-DISC + CO-DRIVER) now translated all 4 languages
  - FR → Voir le prix actuel →
  - NL → Controleer huidige prijs →
  - DE → Aktuellen Preis prüfen →

---

## v5 — 2 April 2026
**File:** index.html
**Commit message:** `drivealert index v5 - button text + hero The fix`
**Keys per language:** 182

### What changed
- Fix: Hardcoded "The" before hero subtitle — hs-pre span, empty in NL/FR/DE
- Fix: Order P-DISC NO3 / Order CO-DRIVER NO2 button texts now translatable
- Fix: pd-btn, co-btn added to translation system all 4 languages
- Fix: Double comma syntax errors cleaned

---

## v4 — 2 April 2026
**File:** index.html
**Commit message:** `drivealert index v4 - dashcam + markets translations`
**Keys per language:** 179

### What changed
- Fix: 13 hardcoded English strings translated NL/FR/DE
- Fix: Markets eyebrow, title, primary/expansion headers
- Fix: Dashcam caption + 4 feature badges
- Fix: Legal FR overseas intro, EN footnote, CH warning
- Fix: cta-sub Three/Drie/Trois/Drei all 4 languages

---

## v3 — 2 April 2026
**File:** index.html
**Commit message:** `drivealert index v3 - Three tools + images + NL bleed fix`
**Keys per language:** 166

### What changed
- Fix: Hero H1 Three/Drie/Trois/Drei all 4 languages
- Fix: NL rv2 translation bleed (French text in Dutch block)
- Fix: Dashcam section (PRODUCT 03) translated NL/FR/DE
- Fix: Real product images in hero cards (no more emojis)
- Add: Nextbase 622GW Schema.org, footer link, SEO block

---

## v2 — 2 April 2026
**File:** index.html
**Commit message:** `drivealert index v2 - Three tools meta + product images`

### What changed
- Fix: Meta description "Two" → "Three smart driving tools"
- Fix: Real product images replace emojis in hero cards
- Add: Nextbase 622GW to footer and SEO block

---

## v1 — March 2026
**File:** index.html
**Commit message:** `Initial commit`

### What changed
- Initial deploy
- Geo-routing JS (NL/BE → Amazon.nl, FR → Amazon.fr, UK → Amazon.co.uk, DE default)
- Multilingual EN/NL/FR/DE
- Affiliate links all markets
- Legal guide by country (4 tabs)
- 3 products: P-DISC NO3, CO-DRIVER NO2, Nextbase 622GW

---

## DEPLOY INSTRUCTIONS — READ EVERY TIME

### Files to upload each deploy
1. index.html
2. CHANGELOG.md (this file — always update version registry before uploading)

### How to deploy
1. Go to: https://github.com/Caeseysolutions/drivealert
2. Click: Add file → Upload files
3. Drag in: index.html + CHANGELOG.md
4. Commit message: see VERSION REGISTRY above for correct message
5. Commit directly to main
6. NEVER use the pencil editor for index.html

### How to name the next version
- Increment version number: v6 → v7
- Date: DD Mon YYYY
- Commit message format: `drivealert index v[N] - [one line description]`
- Add row to VERSION REGISTRY table above before deploying

### Current live version
**v6** · deployed 2 April 2026 · 185 translation keys per language
