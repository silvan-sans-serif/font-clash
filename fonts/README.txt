FONT CLASH — FONTS FOLDER
=========================

/google/
  Future home for Google Fonts downloaded locally (needed for offline app build).
  File naming: FontName-Weight.woff2  e.g. PlayfairDisplay-Regular.woff2

/custom/
  Self-hosted fonts from non-Google sources (OFL, Apache, custom open licenses).
  File naming: FontName-Weight.woff2  e.g. MyFont-Regular.woff2

HOW TO ADD A NEW CUSTOM FONT
-----------------------------
1. Download the font ZIP from the source.
2. Extract and drop the TTF or OTF files into /custom/.
3. Tell Claude which font you added — it will:
   - Convert to WOFF2 if needed
   - Add @font-face declarations to sorts.html
   - Add the font to the correct pool
   - Update font_clash_fonts.xlsx with source, foundry, license, and download URL

LICENSE REMINDER
----------------
All fonts here should be OFL (SIL Open Font License) or Apache 2.0.

