# Fiches de lecture — design mockup

A design mockup for reading cue cards: one card per book or poem, to get back into a favourite book quickly through its key quotes, each shown with its scene.

Open `fiche.html` in a browser. No build step, no dependencies (fonts load from Google Fonts).

## What the mockup shows

- **Cards** sized for a 13.3" laptop screen. The front has the scene, the main quote, a short summary and the characters. The back has other passages and why the book matters. Flip with the ↻ button, a click, or the space bar.
- **Poems** shown whole, scrolling stanza by stanza when they don't fit.
- **Reading language** (French, Icelandic, English, German, Italian), chosen from the "Lire en" dropdown:
  - Each book has its own original language.
  - Published translations carry a translator and edition credit; machine translations are clearly tagged as such.
  - A coloured dot shows the translation quality for each language.
- **Interface language**, set separately under Réglages, together with an italics option.
- **Library** for 100+ cards:
  - search by title or author
  - filters for books and poems
  - sorting by author, title, or recently viewed
  - a random card (*Au hasard*)
- **Read count** on each card (five dots), remembered in the browser.

## Files

- `fiche.html`: the whole mockup (HTML, CSS and JS in one file).
- `livres.md`: flat checklist of all cards; ticked ones have content.

## Caveats

- Only public-domain texts are quoted (Voltaire, Dumas, Hugo, Mann's German original). Quotes from works still under copyright (Camus, Saint-Exupéry, and modern published translations) are left as placeholders: copy them from your own edition for personal use.
- Quotes and the one published-translation credit (the anonymous 1846 English *Monte-Cristo*) were written from memory. Check them against the actual editions before relying on them.
- Translations marked as machine or automatic translations are drafts, not published text.
- 64 of the 70 cards are placeholders ("Fiche à compléter") used to test the library at scale.
