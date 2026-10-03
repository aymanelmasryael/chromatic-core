# Color Math Reference

## Supported Color Spaces

| Space | Example |
|-------|---------|
| HEX | #0074FF |
| RGB | rgb(0,116,255) |
| HSL | hsl(213,100%,50%) |
| OKLCH | oklch(60% 0.20 250) |
| CIELAB | lab(50% 20 -50) |
| CMYK | cmyk(100,55,0,0) |

## Key Formulas

### Luminance (WCAG)

    L = 0.2126 x R + 0.7152 x G + 0.0722 x B

### Contrast Ratio

    ratio = (L1 + 0.05) / (L2 + 0.05)

### WCAG Ratings

- AAA: ratio >= 7:1
- AA: ratio >= 4.5:1
- AA Large: ratio >= 3:1
- Fail: ratio < 3:1
