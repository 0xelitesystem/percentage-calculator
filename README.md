# Percentage Calculator

Four common percentage questions with clearly labeled inputs and live answers. No server, no tracking, no third-party scripts.

**Live demo:** https://0xelitesystem.github.io/percentage-calculator/

## Use

Open `index.html` in any modern browser, or visit the GitHub Pages link in the repo description.

Four modes, each a self-contained card:

- **What is X percent of Y?** Find a percentage of a number (15 percent of 200 is 30).
- **X is what percent of Y?** Turn a part and a whole into a percentage (30 out of 200 is 15 percent).
- **Percent change from X to Y.** Growth or drop between two values, shown as up (green) or down (red).
- **Increase or decrease by a percent.** Apply a positive or negative percentage to a number.

Type into any field and the answer updates as you go. Divide-by-zero and change-from-zero cases are handled instead of showing garbage.

## Why this exists

Percentage calculators online are usually ad-stuffed and load tracking scripts to do arithmetic a phone could do offline. This is the same idea, single file, no analytics, no signup, MIT licensed.

## Privacy

Everything runs in your browser. The numbers you type never leave your machine. Verify by viewing the page source or by opening DevTools and watching the network tab, no requests are made.

## Run locally

```bash
git clone https://github.com/0xelitesystem/percentage-calculator
cd percentage-calculator
# Open index.html in your browser, or:
python -m http.server 8000
```

## Contribute

Issues and PRs welcome:

- More modes (markup and margin, tip splitting)
- Rounding and precision edge cases
- UI improvements (keep it minimal, no frameworks)
- Translations

Don't add: analytics, tracking, external scripts, npm dependencies. The whole point of this tool is no surveillance.

## Build

There is no build. It's a single HTML file.

## License

MIT.

## Related

- [aspect-ratio-calculator](https://github.com/0xelitesystem/aspect-ratio-calculator), simplify dimensions to a ratio and back
- [color-format-converter](https://github.com/0xelitesystem/color-format-converter), convert between HEX, RGB, HSL, and HSV
- [word-and-character-counter](https://github.com/0xelitesystem/word-and-character-counter), count words, characters, and reading time
