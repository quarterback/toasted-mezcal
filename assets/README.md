# Drop-in assets for 0000th

## Video (the front instrument screen)
Place your file here as:

    assets/hero.mp4

It will automatically take over from the animated CSS signal placeholder.
- Export ~1080p, H.264 .mp4, muted (it autoplays silently and loops).
- The screen uses object-fit: cover, so any aspect ratio fills cleanly.
- Want a poster frame before it plays? Add assets/hero-poster.jpg and set
  poster="assets/hero-poster.jpg" on the <video> in 0000th.html.
- To also offer .webm, add a second <source src="assets/hero.webm" type="video/webm">.

## Fonts
Put .woff2 files in assets/fonts/ and uncomment the @font-face blocks at the
top of styles.css, then set --font-display / --font-mono to your families.

## Email
Replace contact@0000th.org in 0000th.html (one place, the mailto link).
