---
title: Vault Changelog
type: index
category: navigation
status: living document
tags:
  - index
  - changelog
---

# Vault Changelog

> One entry per cleanup pass. Every fix names its reason and its source of truth, so canon never drifts silently again.

---

## 2026-09-09 — Pass 1: Structure, Naming & Canon Sync

### 1. Naming convention (author request: no underscores, anywhere)
* Every file and folder renamed from underscore style to spaced names — e.g. the Master Index, the Act Map, the Chapter Outline, the Story Compass, the Secrets & Twists Ledger, and all character files (Kyrell Mavaros, Adira Solari, and the rest).
* All 144 wiki links across the vault were rewritten to the new paths and machine-verified — zero broken links.
* Two naming judgment calls (veto either): the isles folder is **The Sun-Gilded Isles** (hyphenated proper noun, matching the prose), and Theron's file is **Theron of Clan Korvos** (his proper style, not the old compressed form).
* Obsidian tags cannot contain spaces, so tag underscores became hyphens (e.g. faction tags like sun-gilded-isles). Frontmatter status and category values now use spaces.
* App internals (the hidden Obsidian config folder) were left untouched.

### 2. Structure (nothing was lost — the deletion was a verified duplicate)
* **Deleted:** the duplicate reference folder — all four files were byte-identical copies of the planning docs in 07 Planning, which remains the single source of truth.
* **Created 05 Manuscript** and moved the three chapter drafts into it — this fills the numbering gap between 04 and 06 that the README and Master Index already promised.
* The stray root dev log now lives in Planning as **Book 1 Dev Log - Brought Before Kyrell**.
* The **Style Spec Voice Bible** moved into 00 Index, beside the Style Guide (which now cross-links it).
* The **Adira Capabilities & Limits** sheet moved in beside her character file.
* Removed a leftover git config file at the vault root (git never reads one there; it was dead weight).
* Known gap (flagged only): the dev log's changelog mentions a map brief and a map plan file that are not in this vault. If they live on your machine, drop them in and they will be relinked.

### 3. Canon fixes (each synced to a decision already locked in the vault)
1. **Kyrell's glyph list** now uses the canonical grimoire names — Strength, Speed, Kinetic Deflection Shield, Point-Blank Kinetic Shock; Manifestation, Partial Manifestation, Surface Spread, Extended Reach. (The old list — "Kinetic Shockwave, Burst Step, Shadow Coat" etc. — matched nothing in the canon grimoire.)
2. **Lucan's two glyphs** likewise corrected to Speed and Kinetic Deflection Shield, with canonical placements.
3. **Duke Thalor's conflict paragraph** no longer claims he hunts Adira's vessel and artifacts — locked canon says the catastrophe is a storm and no one knows the islanders exist. His real Book 1 thread is the secret armada.
4. **Inquisitor Crane's Book 1 role** corrected: he runs the purges and hunts Kyrell's networks; the manhunt for the thieves is Kyrell's own network until the Act IV counter-hunt. His end-of-book fate stays open.
5. **Ronan** no longer "knows she hated the betrothal" — locked compass and the Ch1 draft say she fully accepted it as duty.
6. **The Abyssal Gyre** in the twists catalog is marked OPEN (mechanism undecided, do not lock), matching the Adira capabilities sheet.
7. **Ch12's courier-pouch task** marked vetoed in the outline, per the dev log decision table; replacement open.
8. **The handmaiden** is now consistently "Sera (working name)" across compass, act map, and outline — her characterization is locked (competent, steady organizer-healer); her full identity remains open.
9. **Master Index & README:** added Master Koa, the Manuscript and Planning sections, the Voice Bible, and the capabilities sheet; fixed the magic bible blurb (the 16 are glyphs, not laws).
10. **Series Architecture:** removed a stray LaTeX arrow artifact; the Book 1 line no longer says the leads "destroy" Crane — the outline leaves his fate open.
11. **Trilogy Overview:** the resolution no longer binds the leads with a "pulse-tether" (locked rule: no magical bond, no fated mates) — they are bound by choice.
12. **Book 1 Overview page:** status refreshed — the act map and chapter outline now exist in Planning; the page keeps the fixed starting points.

### 4. Awaiting the author's call (flagged, deliberately untouched)
* **Escort count:** the compass says five guards *including* Ronan (four dead); the outline, act map, dev log, and the Ch2 draft all say five guards died besides Ronan.
* **First confrontation timing:** the compass says Adira stands before Kyrell by ~Ch5; the detailed outline places the capture and confrontation at Ch9.
* **Twist 4** in the twists catalog (the tongue-inked prince whispering command frequencies) breaks the hard no-mind-control rule and contradicts Corin's canon — replace, discard, or keep?

---

## 2026-09-09 — Pass 2: Batch II timeline locked

* **Decision (author-confirmed): the Batch II experiments happened 18 years ago.** Kyrell was fourteen — a true child of the gutters, matching Lucan's locked story (he met Kyrell at 14, half-dead out of the northern flumes, and has stood beside him for the 18 years since).
* Kyrell's file corrected from "15 years ago" to "18 years ago, at age fourteen." Lucan's file needed no change.
* Corin's "15 years ago" dates (the stasis awakening and Vance's death-lie) are a separate timeline and remain untouched.
---

## 2026-09-09 — Pass A applied: The Leads (author rulings)

* **Bulk-ratified:** 27 lead facts locked into the Canon Status Register (identities, magic, weapons, limits, arcs).
* **Ruling — bare-hands trope removed:** "gloves off = intimacy/vulnerability" declared cliche and erased everywhere it appeared (the Glove Strip custom, the style guide & voice bible beats, the compass armor line, Kyrell's appearance box). Gloves stay as wardrobe + palm-glyph concealment; touch-starvation continues via wound-tending, the almost-touch, the mantle-drape, the three-dance rule.
* **Ruling — height:** Adira is 5'5" (165 cm), corrected from 5'8".
* **Ruling — English only:** all island-language words removed (te Solari, Te Hā, The Umu); customs renamed in English (the Obsidian Breath, the Communal Earth-Oven); the Ch1 draft prose patched to match.
* **Ruling — junction faults (1A):** the Circuits-doc mechanical version is canon; Kyrell's file now carries the three glyph-pair faults + the bloom tell instead of the old symptomatic list.
* **Ruling — the locket:** no maternal warning exists. The locket is an unexplained gift — Adira knows what it holds, never why her mother sealed Mountain Blood inside. Updated across her file, the Mount Kora doc, the compass, and the secrets ledger (the "guide you home" seed superseded by "the unexplained purpose" seed, payoff Book 3).
* **Ruling — "The Unmarked Bride" alias (3B):** dropped; parked in the register graveyard.
* **Ruling — glyph origin (4A):** all 8 of Kyrell's glyphs were inked during Batch II at age 14.
* **Open (A-29):** who can read Kyrell's micro-tells/junction fatigue — clarification requested.
---

## 2026-09-09 — Pass A follow-up: A-29 resolved (option c)

* **Ruling:** she reads Kyrell the way any attentive person reads someone they're falling for — **no special tell-reading ability, no "only one alive" claim**. Applied across her file (the "Observational Genius / Only Reader of His Ink" skill removed), the capabilities sheet, the style guide & voice bible, the circuits doc (now "No Unique Reader" — anyone paying attention can learn the flickers), the compass symmetry, the act map (Ch19–20), the outline's locked Ch13 beat (the flicker stays; "She alone can read it" removed), the dev log, the ledger, and Kyrell's file.
* The Ch13 "she says *Kyrell* — something flickers under his collar" beat survives: the ink-flicker physics are magic canon; the noticing is now ordinary attentiveness.
