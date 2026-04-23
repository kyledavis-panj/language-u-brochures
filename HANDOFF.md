# Language U — Project Handoff

> **For Lia's future Claude session.** Paste this whole document into your first message so Claude instantly has the full context of everything we built together. It's long — that's the point. Claude will read fast.

---

## 0. How to use this doc

**If you're Lia (or any future Claude working for Lia):**

1. Save this doc or keep the repo URL handy
2. In a new Claude session, paste this message as the first thing:

```
I'm Lia Andrews, founder of Language U (www.languageuniv.com).
I'm continuing a project that was started in an earlier Claude session.

Here's the full project context — please read this before we start:

[PASTE THE CONTENTS OF THIS HANDOFF.md HERE]

Here's the source repo (public): https://github.com/kyledavis-panj/language-u-brochures
Here's my shared Drive folder: https://drive.google.com/drive/folders/1UYKo91oIV9uPq581Tanb79nVM4s_2aGj

Now let's pick up where we left off.
```

3. From there, talk to Claude normally. It will have everything.

---

## 1. Who I am

- **Lia Andrews** — founder of **Language U**, a Spanish program for children in early childhood (ages 2–6 core; library programs extend to 5th grade)
- Based in Wilmington, DE, serving Southeast PA + DE + Northern MD
- Education: BA French + Spanish minor (West Chester), Master's in French (Middlebury College)
- Started teaching kids in 2008, founded Language U
- My husband **Kyle Davis** often helps orchestrate the tech/dev side (he was driving the Claude Code session where most of this was built)
- Brand values: warmth, joy, play, cultural celebration, early childhood as sacred developmental window

**My voice:** Warm, enthusiastic, teacher-y, mission-driven. Uses emojis sparingly. Avoids academic jargon. Inspired by Mr. Rogers, Sesame Street, and the Muppets.

**Rule I live by:** *"If it doesn't feel like joy, it isn't on brand."*

---

## 2. The project in one paragraph

A multi-day collaboration where Claude + Kyle built out design and communication assets for Language U — including a redesigned library program brochure, a Meet Dino mockup web page with an interactive chat widget, social post concepts, posters, stickers, a brand reference guide, Squarespace copy for a new page, and a voice recording script. Everything is captured in a GitHub repo and a shared Google Drive folder. The most recent push was the **library brochure v2 final** with Lia's full brand kit applied.

---

## 3. Brand spec (the most important section)

### Colors
| Name | Hex | Use |
|---|---|---|
| Red | `#E81C47` | Primary accent, pricing emphasis |
| Navy | `#2C327C` | Primary/text/outline |
| Yellow | `#F6D156` | Highlights, drop shadows |
| Teal | `#71CCD6` | Secondary accent |
| Coral/Peach | `#F49D78` | Warm accent |
| Dark Neutral | `#373A46` | Body text |
| Light Neutral | `#F7F8E9` | Background |

### Typography
| Role | Adobe font (real) | Google Font substitute |
|---|---|---|
| Display/Header | **Caraque Regular Melted** | Fredoka |
| Subheader | **Galvji Regular** | DM Sans |
| Body | **Bely Regular** | Lora |
| Accent/CTA | **Caraque Bold Melted Caps** | Fredoka Bold |

*Adobe fonts are what I actually use. Claude uses the Google substitutes in HTML/PDF rendering. When opening source files in Canva with real Adobe fonts, swap them.*

### Characters (the paper-cut amigos)
- **Dino** — red T-rex, sandwich-obsessed, goofy, my primary teaching character
- **Chico** — boy student, brown hair, warm skin tone
- **Chica** — girl student, long dark hair, warm skin tone
- **Patito** — yellow rubber duck with a purple shower cap
- **Sandwich** — standalone prop (wheat bread, ham, cheese, tomato, lettuce)

All character assets live in `/assets/characters/` in the repo + in the shared Drive folder.

### Taglines (use these)
- **Primary:** "We don't teach Spanish. We play in it."
- **Mission:** "Changing the world, one word at a time."
- **Campaign:** "Spanish Adventures"
- **Fiesta:** "Learning Spanish should feel like a fiesta!"
- **Reach:** "The earlier the language, the bigger the world."
- **Simple:** "Fluency starts with fun."

---

## 4. Dino's voice canon (locked in)

Dino is a character. When anything is written from Dino's perspective (letters, chat responses, social copy), his voice is:

- **Goofy, cheesy, dad-joke king** — groan-worthy puns welcome
- **Sandwich-obsessed** — mentions sandwiches whenever possible 🥪
- **Self-aware of tiny T-Rex arms**
- **Mixes English + Spanish naturally** with pronunciation hints baked in (e.g., *"¡ROJO! (ROH-ho) That's red!"*)
- **All-caps for excitement**, sparingly
- **Never scolds, corrects, or talks down to kids**
- **No bathroom humor beyond saying "poop" (popó) as a word**

### Dino's signature sign-off (ALWAYS use, verbatim)

```
Con mucho amor y un sándwich,
Dino 🦖🥪
```

This is locked in memory and should appear at the end of every Dino-authored message.

---

## 5. What we've built (inventory)

### Live at URLs (share with anyone)

| Asset | URL | What it is |
|---|---|---|
| **Library brochure repo** | https://github.com/kyledavis-panj/language-u-brochures | This repo — brochure source + final PDF |
| **Library brochure (live preview)** | https://kyledavis-panj.github.io/language-u-brochures/src/brochure.html | HTML version renders in browser |
| **Library brochure (final PDF)** | https://kyledavis-panj.github.io/language-u-brochures/output/Library_Brochure_v2.pdf | Send this to libraries |
| **Meet Dino mockup hub** | https://kyledavis-panj.github.io/language-u-mockup/ | Other mockups (chat widget, posters, stickers, brand guide) |
| **Meet Dino page (interactive chat)** | https://kyledavis-panj.github.io/language-u-mockup/meet-dino/ | Chat with Dino demo — 50 Spanish questions + shuffle |

### In the shared Drive folder (LIA CLAUDE WORK)

- `Library Brochure — Fall (v2 FINAL — Lia's edits).pdf` — the production PDF
- `Dino voice sample (for ElevenLabs).mp3` — 4:51 of pure Dino voice extracted from YouTube (if/when voice cloning)
- `Dino Voice Recording Script.html` — 50-line script for me to record in Dino's voice
- `Meet Dino Squarespace Copy.html` — ready-to-paste content for a new /meet-dino page on my website
- `Brand Guide.html` — full color/typography/character/voice reference
- All finished posters, stickers, social post PNGs
- `Logos/` — all Ü icon variants, stacked logo, horizontal logo, `LU_refined.pdf`
- `Characters/` — full paper-cut character library
- Source photos: `book kids.HEIC`, `messy photo.HEIC`

---

## 6. Key decisions captured (so future Claude doesn't re-litigate)

### Library brochure
- **Pricing:** Story-Times **$70 single / $325 5-pack** (save $25); Workshops $150/$175; Concerts $225 (Northern DE); Custom starting at $70
- **Concert wording:** *"Live music show performed in English with target Spanish words and songs woven throughout"* — NOT "bilingual music show"
- **Age range on cover:** "Toddler–5th" (NOT "2–11 yrs")
- **Story-Times pitch:** opens kids' minds to *"language, equity, culture and curiosity"*
- **Hero photo:** The "messy selfie" with me + kids + Dino + Patito, cropped from the top to reduce classroom background
- **Character names in lists:** NO emojis next to them (Dino · Chico · Chica · Patito, plain text)
- **Second paragraph phrasing:** "Allow me to join you at your branch with my amigos, a bag of shakers and some serious silliness" — NOT "a little bit of magic" (avoided the magic-tricks implication)
- **Origin story:** "In 2008, I created my own company (Language U) and built out my Spanish Adventures program — grounded in music, puppets, movement, and my favorite teaching tool: storytelling."
- **Word choice:** "children" NOT "young kids"
- **Tagline pill:** Yellow pill, navy border, navy text, slight tilt (kept the original design)
- **QR code on page 2:** Links to my YouTube read-aloud https://youtu.be/_fNGsykGaq4

### Meet Dino web mockup
- Interactive chat widget with 50 Spanish learning questions + 🎲 shuffle
- Dino's responses include pronunciation hints
- Mobile-optimized (full-screen modal, 16px inputs, 44x44 tap targets)
- Built as HTML/CSS/JS, hosted on GitHub Pages

### Voice cloning (deferred)
- ElevenLabs Instant Voice Clone moved behind paywall (Starter plan $5/mo)
- Alternative: I record 50 lines myself using phone voice memos → script exists at `docs/dino_voice_script.html`
- Either path unlocks Dino speaking in my real voice in the chat widget

### Amy Poehler podcast outreach
- 6 draft emails created (3 + 3) pitching a shout-out on "Good Hang" podcast for me / Dino / Language U
- Sent to my inbox for review, awaiting my pick
- Drafts cover: husband's love letter, letter written FROM Dino, classroom scene, Ms. Lia screamed at the podcast, business-memo parody, music pitch

---

## 7. What's pending / decision still needed

1. **Dino voice** — pick a path (record 50 lines OR pay ElevenLabs)
2. **Amy Poehler email** — pick a draft + Kyle sends from his professional email
3. **Website changes on languageuniv.com** — pricing discoverability fixes discussed (add "starting at $X" to closed accordions, promote "first class free" to page header, default-open one school)
4. **Meet Dino page on Squarespace** — copy doc is ready (`Meet Dino Squarespace Copy.html`), just needs to be implemented in Squarespace
5. **Reactions to any of the 7 emails sent to me over the last few days** — lots of design directions awaiting my input

---

## 8. How to continue the brochure specifically

The brochure source is in the repo at `src/brochure.html`. It's pure HTML/CSS with inline styles — no build tools, no dependencies beyond Google Fonts.

### To edit
1. Clone the repo: `git clone https://github.com/kyledavis-panj/language-u-brochures.git`
2. Open `src/brochure.html` in a text editor OR ask your Claude to edit it
3. Preview locally: run `python3 -m http.server 8000` in the `src/` folder, then open `http://localhost:8000/brochure.html`

### To regenerate the PDF
```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless --disable-gpu --no-sandbox \
  --print-to-pdf=output/Library_Brochure_v2.pdf \
  --print-to-pdf-no-header \
  http://localhost:8000/brochure.html
```

(Run headless Chrome against the local server — not against the file directly, since the HTML references local image files.)

### To push changes back to GitHub
Need write access to the repo. Currently only Kyle's `kyledavis-panj` account has push rights. Options:
- Kyle adds me as a collaborator
- Or I create my own GitHub account + fork it
- Or I work locally and send finished files to Kyle, who pushes

---

## 9. Preferences I've shown (for future Claude to match)

- **Move fast when I'm moving fast** — batch edits, don't ask for confirmation on every little thing
- **Ask me to confirm before big creative changes** — never surprise me with a whole rewrite
- **Give me options, not open questions** — I prefer "here are three ways, pick one" over "what do you want?"
- **Honor my exact phrasing** when I give you a line — don't "improve" my wording unless I ask
- **Be honest when your first take missed the mark** — I'd rather you catch a mistake than defend it
- **Stick to my brand colors and voice religiously** — if you don't have the real spec, ask

---

## 10. Kyle's role

Kyle is my husband and the business ops half of Language U. He's often the one running Claude Code sessions on his laptop doing implementation work (deploys, uploads, GitHub pushes, Google Drive operations). He has access to:
- Full admin of the `kyledavis-panj` GitHub account
- Full access to the shared Drive folder
- Kyle's Gmail at `kyledavis@sculpturehospitality.com` (used for sending emails on my behalf)
- His own ElevenLabs account (free tier) — only relevant if we pursue voice cloning

If something needs to be **pushed/deployed/uploaded**, Kyle can do it. If it's a **creative call**, it's mine.

---

## 11. The handoff moment

This document was written on **April 23, 2026** at the end of a session where Claude and Kyle were wrapping up the library brochure v2. My laptop isn't yet set up with Claude Max, so future-me will inherit this project when I'm ready.

Future-me: welcome. You're picking up something good. Have fun with Dino. 🦖🥪

— Claude (with Kyle, for Lia)
