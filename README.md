## Description

A mobile-ready Japanese learning app focused on kanji and JLPT vocabulary.

The app combines kanji data (readings, meanings, JLPT level) with related vocabulary, creating a structured learning experience where each kanji is linked to real words.

Features:
- Kanji by JLPT level (N5–N1)
- On’yomi and Kun’yomi readings
- Linked vocabulary for each kanji
- Quiz-style learning approach
- Fully offline dataset (no API required)

Data is sourced from open datasets and transformed into a custom structure optimized for fast usage in the app.


## Data Sources

This project uses external open-source datasets for Japanese kanji and vocabulary.

### Kanji Data
Source:
https://github.com/davidluzgouveia/kanji-data

License:
MIT License

Description:
Kanji dataset including readings (on/kun), meanings, stroke count and JLPT-related information.
Originally based on KANJIDIC data, provided by the Electronic Dictionary Research and Development Group.

---

### JLPT Vocabulary Data
Source:
https://github.com/jamsinclair/open-anki-jlpt-decks

Description:
Vocabulary lists for JLPT levels N5–N1, including word, reading and meaning.
Used as the base for vocabulary associated with kanji in this application.

---

### Attribution

Kanji data is derived from KANJIDIC, property of the Electronic Dictionary Research and Development Group.

This project does not claim ownership of the original datasets.
All rights belong to their respective authors.

---

## Usage

This project may be used, copied, modified, and distributed freely.

However, it may not be sold, monetized, or redistributed as part of a paid product or paid service without explicit permission from the author.

The datasets used in this project remain subject to their original licenses and attribution requirements.

---

### Notes

The datasets have been transformed and combined into a custom structure for use in this application.
