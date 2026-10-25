# Font Details

## Logos

The logos use Outfit, a free geometric sans-serif from Google Fonts (released under the SIL Open Font License, so it’s fine for commercial use).

Wordmark (“halfaversary”): Outfit Medium (weight 500), set in lowercase with slightly tight letter spacing (-0.03em).
Tagline (“Celebrate the Journey”): Outfit Regular (weight 400) at 15px, in all caps with wide letter spacing (0.28em).

The two other palettes I made earlier used different fonts. The Garden board used Fraunces, a serif, and the Pop board used Space Grotesk. Those boards were removed from your canvas, though.

If you plan to use the logo in print or on a website, I’d recommend converting the text to outlines in your design software or exporting the final logo as an SVG or PNG, so it doesn’t depend on the font being installed.

## CSS to Match Logos

Notes:

The wordmark is lowercase in the HTML. The tagline is typed normally and text-transform: uppercase makes it all caps.
The wide letter spacing adds a little extra space after the last letter of the tagline. To center it exactly, add padding-left: 0.28em or margin-right: -0.28em.
Because the sizes use px, scale the wordmark and tagline together. For example, if you set the wordmark to 42px, use about 7.5px for the tagline. The letter spacing is in em, so it scales automatically.

For the pink version, use #D43FA0 in place of #FF6B4A.

<span style="display:inline-block;width:16px;height:16px;background-color:#FF6B4A;border:1px solid #ccc;vertical-align:middle;"></span> #FF6B4A

<span style="display:inline-block;width:16px;height:16px;background-color:#D43FA0;border:1px solid #ccc;vertical-align:middle;"></span> #D43FA0

### HTML

```
<link rel="stylesheet"
  href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;500&display=swap">

```

```
<div class="wordmark">halfaversary</div>
<div class="tagline">Celebrate the Journey</div>

<div class="wordmark">half<span class="accent">a</span>versary</div>

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

.wordmark .accent { color: #FF6B4A; }

.tagline {
    font-family: 'Outfit', 'Helvetica Neue', Arial, sans-serif;
    font-size: 15px;
    font-weight: 400;
    letter-spacing: 0.28em;
    text-transform: uppercase;
    color: #6B6475;
}

```
