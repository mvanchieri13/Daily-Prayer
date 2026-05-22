# Liturgy of the Hours

A minimal, mobile-first Catholic daily prayer app based on the traditional Liturgy of the Hours.

## Features

- Six canonical hours: Lauds, Terce, Sext, None, Vespers, Compline
- Auto-selects the current hour based on time of day
- 15-second silence prompt to settle before each prayer
- Daily intention at Lauds
- The Angelus at Sext (midday)
- Act of Contrition + Examen at Compline
- Salve Regina to close the night
- Visited hour indicators
- Works as an iPhone home screen app

## Install as iPhone App

1. Open the site URL in **Safari**
2. Tap the **Share** button → **Add to Home Screen**
3. Name it "The Hours" and tap Add

## Hosting

This is a single `index.html` file with no dependencies or build step.
Deploy to GitHub Pages by enabling Pages in your repository settings (Settings → Pages → Deploy from branch → main → / root).

## Structure

All content is self-contained in `index.html`. To modify prayers, edit the `HOURS` array in the `<script>` block.
