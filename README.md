# Caesar Cipher Encoder/Decoder

A simple, fast, browser-based Caesar cipher tool — encrypt and decrypt text with a configurable shift value, styled with Tailwind CSS and a dark-mode toggle.

## Features

- **Encrypt / Decrypt** — shift text by any value from 1 to 25 (default 3), the classic Caesar shift.
- **Live updates** — results recompute instantly as you type or change the shift.
- **Copy to clipboard** — one-click copy of the result.
- **Clear all** — reset the form in one click.
- **Dark mode toggle** — light/dark themes that switch instantly.
- **100% client-side** — no server, no login, no data ever leaves your browser.

## Tech Stack

- HTML5, CSS, vanilla JavaScript
- Tailwind CSS (via CDN)

## Quick Start

No build step needed. Either:

1. Open the [live demo](https://girishlade111.github.io/Caesar-Cipher-EncoderDecoder/) in your browser, or
2. Download `index.html` and open it directly — it runs offline (an internet connection is only needed for the Tailwind CDN styling).

Type your text, pick a shift value (1–25), and hit **Encrypt** or **Decrypt**.

## Project Structure

```
Caesar-Cipher-EncoderDecoder/
└── index.html   # The whole app: UI + cipher logic + theme toggle
```

## How It Works

Each letter `A–Z` / `a–z` is rotated forward (encrypt) or backward (decrypt) through the alphabet by the shift value, wrapping around at the ends. Non-alphabetic characters are left untouched.

## Deploy Notes

Static site hosted on GitHub Pages — served directly from the `main` branch. No build, no secrets, no environment variables.

## Contributing

Found a bug or want a feature (e.g. ROT13 preset, brute-force mode)? Open an issue or a pull request — contributions are welcome.

---

Built by **Girish Lade** — [ladestack.in](https://ladestack.in)
