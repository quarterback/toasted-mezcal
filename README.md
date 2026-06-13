# 0000th

A static, single-screen holding page for 0000th — a stealth, AI-native company.

Implemented from the Claude Design handoff bundle (`0000th - intro.html`): a
font-forward, no-scroll intro in the established ink/celadon palette.

## Layout

- **Wordmark** (top-left) — `0000ᵗʰ` in **Epilogue Black**, the dominant mark.
- **Contact** (bottom-left) — a single `mailto:` link in **Azeret Mono**.
- **Background** — a pure-CSS parallax cityscape (three tower layers drifting at
  different speeds, with a breathing horizon glow). No asset required.

Type: Epilogue Black (mark) · Switzer (sans) · Azeret Mono (chrome), loaded from
Google Fonts / Fontshare. Palette: Ink `#001a23`, Alice `#e8f1f2`,
Celadon `#b3efb2`.

## Real footage (optional)

The page has a video slot layered over the CSS city. Drop a muted, looping
1080p H.264 `.mp4` in at `assets/hero.mp4` and it fades in over the CSS
background once it has data; if it fails to load, the CSS city stays. See
`assets/README.md` for export tips.

## Running

It's a static page — open `index.html` directly, or serve the folder:

    python3 -m http.server
