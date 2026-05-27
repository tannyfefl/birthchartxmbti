# Birth Chart × MBTI

A whimsical Hendrick's-inspired registration form that generates a tiny astrological + MBTI reading for whoever fills it in.

## What it does

Collects basic details (name, phone, email, date / time / place of birth) and produces a small "Cabinet of Curiosities" reading:

- ☀ Sun · ☾ Moon · ↑ Rising
- MBTI temperament with a hand-illustrated character (16 in total, e.g. *The Velvet Cartographer*, *The Comet Catcher*, *The Iron Conductor*)
- A kindred-spirit MBTI and a worthy-adversary MBTI, each with their own character + line-art illustration
- A "soul city" your sun sign sends you to

There's also an admin **Ledger** view to browse / search / export every submission as CSV.

## Run it

It's a single self-contained HTML file — no build, no server, no dependencies (other than Google Fonts).

```bash
open contact-form.html
```

Or host it on GitHub Pages directly.

## Stack

- Vanilla HTML / CSS / JavaScript
- Google Fonts: IM Fell English, Cormorant Garamond, Inter
- `localStorage` for persistence (with in-memory fallback)

## Honest caveat

Sun signs are calculated properly from the birth date. Moon, Rising, and MBTI are deterministically derived from the birth data — same input always produces the same output, but it's not astronomically/psychometrically accurate. It's for fun.
