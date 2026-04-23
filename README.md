# Language U — Library Brochure

Source files and final PDF for Language U's **Spanish Adventures at the Library** program brochure.

## 📁 What's in here

### `src/` — Everything the brochure HTML needs to render
- **`brochure.html`** — Source HTML/CSS. Open in a browser to preview. Uses free Google Fonts as stand-ins for the real Adobe fonts (Caraque Melted / Galvji / Bely).
- Character PNGs: `char_dino.png`, `char_chico_spring.png`, `char_chica_spring.png`, `char_patito.png`
- Logo: `logo_horizontal.png`, `icon_navy.png`
- Photo: `messy_photo.jpg` (cropped hero image)
- QR code: `qr_readaloud.png` (links to YouTube read-aloud)

### `output/` — Final PDF
- **`Library_Brochure_v2.pdf`** — The latest version. This is the file to send to libraries.

### `assets/` — Full asset library
Extra character poses, all logo variants, and photo options not currently used in the brochure but available for future iterations.

- `assets/characters/` — Full Dino + amigos set (multiple poses)
- `assets/logos/` — Logo-01, Logo-02, all 6 Ü icon variants, refined brand guide PDF
- `assets/photos/` — `messy_photo.jpg` + `book_kids.jpg`

## 🎨 Brand reference

The brochure uses the official Language U palette:

| Name | Hex |
|---|---|
| Red | `#E81C47` |
| Navy | `#2C327C` |
| Yellow | `#F6D156` |
| Teal | `#71CCD6` |
| Coral | `#F49D78` |
| Dark Neutral | `#373A46` |
| Light Neutral | `#F7F8E9` |

## 🔁 How to update the brochure

1. Edit `src/brochure.html` — copy, characters, prices, etc.
2. Open locally in a browser to preview, OR run a local static server (`python3 -m http.server 7845`) from `src/`.
3. Regenerate the PDF with headless Chrome:
   ```
   "/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless --disable-gpu --no-sandbox \
     --print-to-pdf=output/Library_Brochure_v2.pdf \
     --print-to-pdf-no-header \
     src/brochure.html
   ```
4. Commit + push.

## 🔗 Related

- **Meet Dino mockup:** [kyledavis-panj.github.io/language-u-mockup](https://kyledavis-panj.github.io/language-u-mockup/) (chat widget + social post mockups + brand guide)
- **LIA CLAUDE WORK Drive folder:** shared with Lia, contains full brand kit + source photos

## 🙏 Credits

- Design + brochure rebuild: Claude (via Kyle)
- Brand, voice, characters, and business: Lia Andrews, Language U
- Website: [languageuniv.com](https://www.languageuniv.com)
