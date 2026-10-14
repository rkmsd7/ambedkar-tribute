# Dr. B.R. Ambedkar · A Life

A static tribute site tracing Babasaheb Ambedkar's life from Mhow (1891) to Deekshabhoomi (1956) and beyond: a filterable timeline with photographs, writings, speeches, public appearances, videos, and the Twenty-two Vows. Published 14 October 2026, seventy years after the Dhammachakra Pravartan at Nagpur.

## Run locally
```
node serve.js        # http://localhost:4174
```
No build step. Pages render from `data/*.json` (schema in `data/SCHEMA.md`).

## Edit content
Edit the JSON, not the JavaScript:
- `data/timeline.json` – eras and dated events (`media` may name an image id)
- `data/images.json` – Wikimedia Commons photographs with licences
- `data/videos.json` – YouTube IDs (verified via oEmbed)
- `data/writings.json`, `data/speeches.json`, `data/appearances.json`, `data/quotes.json`, `data/vows.json`, `data/site.json`

## Sources
Dr. Babasaheb Ambedkar: Writings and Speeches (Govt. of Maharashtra, 17 vols.); Constituent Assembly Debates; Dhananjay Keer, *Dr. Ambedkar: Life and Mission*; Columbia University Ambedkar collection (Frances Pritchett). Text © CC BY-SA 4.0. Images retain their Commons licences.
