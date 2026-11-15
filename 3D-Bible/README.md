# 3D-Bible

An interactive 3D visualization of the Bible's 66 books, built with Muse (Omi). Each book is a translucent tower: its height is its chapter count, each chapter is a layer, and each verse is a block in a square grid on its layer.

- All 66 books in canonical order (1,189 chapters, 31,102 verses), rotatable in 3D, with a flat 2D grid view
- Tap a book to isolate it; pick chapters and verses, highlight verses in yellow, and read the text in English, Traditional Chinese, or Japanese
- Search by reference or by text, save highlight sets as templates, and follow Strong's numbers from a verse's word list to every occurrence

## Files

- `3D-Bible.html` — the complete app as one self-contained HTML file. Open it in any browser; no server or build step needed. (Verse text and search load live from free Bible APIs, so the reading features need an internet connection.)
