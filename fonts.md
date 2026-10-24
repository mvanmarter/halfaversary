# Font Details

## Logos

The logos use Outfit, a free geometric sans-serif from Google Fonts (released under the SIL Open Font License, so it’s fine for commercial use).

Wordmark (“halfaversary”): Outfit Medium (weight 500), set in lowercase with slightly tight letter spacing (-0.03em).
Tagline (“Celebrate the Journey”): Outfit Regular (weight 400) at 15px, in all caps with wide letter spacing (0.28em).

The two other palettes I made earlier used different fonts. The Garden board used Fraunces, a serif, and the Pop board used Space Grotesk. Those boards were removed from your canvas, though.

If you plan to use the logo in print or on a website, I’d recommend converting the text to outlines in your design software or exporting the final logo as an SVG or PNG, so it doesn’t depend on the font being installed.

## CSS to Match Logos

### HTML

```
<link rel="stylesheet"
  href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;500&display=swap">
```

### CSS

```
.wordmark {
    font-family: 'Outfit', 'Helvetica Neue', Arial, sans-serif;
    font-size: 84px;
    font-weight: 500;
    letter-spacing: -0.03em;
    line-height: 1;
    color: #1F1B2D;
}

.tagline {
    font-family: 'Outfit', 'Helvetica Neue', Arial, sans-serif;
    font-size: 15px;
    font-weight: 400;
    letter-spacing: 0.28em;
    text-transform: uppercase;
    color: #6B6475;
}
```
