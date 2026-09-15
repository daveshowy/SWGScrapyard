# Scrapyard

A browser-based vehicle component / reverse engineering planner for **Star Wars Galaxies: Restoration**.

- Read parts straight from the game: share your SWG window, draw a box over a component's examine window, and click through your parts. Scrapyard OCRs each one and adds it to your stash automatically.
- Colour-coded stash by component type, with parts that add nothing flagged so you don't waste Tuning Modulators.
- Shows the RE result of everything you own per slot, and the fewest parts needed to reach all-blue / all-green.
- Shopping list of the attributes you still need, and whether a bazaar part would fill the gap.
- Sub-system balance planner (Mass / Cooling / Stabilizer / Energy).

**Read-only.** Scrapyard never sends input to the game client, reads game memory, or modifies any client file. It only looks at pixels you choose to share. OCR runs in your browser; nothing is uploaded anywhere.

## Use it

Open the hosted page, or download `index.html` and open it in Chrome/Edge. Screen share needs the page served over https or opened as a local file.

Formulas and attribute lists follow the [swgr.org vehicle wiki](https://swgr.org/wiki/vehicle/).

## Credits

Built by OnePound Fish. Uses [Tesseract.js](https://github.com/naptha/tesseract.js) for OCR.
