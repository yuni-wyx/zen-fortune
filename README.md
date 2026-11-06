# 一念之籤 · A Moment of Fortune

A lightweight, bilingual (Traditional Chinese / English) interactive fortune-drawing website.

## Features

- 100 original fortunes with interpretations in Chinese and English
- Animated fortune cup and bamboo-style shake/reveal sound effects
- Mobile shake-to-draw using the DeviceMotion API (requires browser permission on iOS)
- Responsive layouts and language toggle
- Cloudflare Web Analytics integration

## Run locally

This site uses plain HTML, CSS and JavaScript. Open `index.html` in a browser or serve the folder with a local static server:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

For mobile motion sensors, use an HTTPS website (or browser-supported secure localhost), and tap **Enable shake to draw** before shaking.

## GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Set **Build and deployment → Deploy from a branch**.
3. Select **main** and **/(root)**, then save.
4. After GitHub finishes publishing, the expected project URL is:
   https://yuni-wyx.github.io/zen-fortune/

GitHub Pages availability for private repositories depends on the GitHub plan. If your plan does not support Pages from this private repository, you can change visibility to public or choose an alternative host.

## Analytics

The Cloudflare Web Analytics beacon is embedded near the end of `index.html`. To view visit metrics, use the Web Analytics site configured in the Cloudflare dashboard. If you move the site from its earlier hostname, update the hostname in Cloudflare Web Analytics and verify that traffic is being received.

All fortune content is original and for reflection/entertainment rather than religious or professional advice.
