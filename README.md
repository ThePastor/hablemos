# Hablemos

Learn **Spanish** from the first word to reading García Márquez in the original — six levels, a verb trainer, six games and a house full of companions you raise as you go. It installs to a phone and works with no connection.

**Live app:** https://thepastor.github.io/hablemos/

---

## What it does

- **Six levels**, from the alphabet and greetings through to reading a novel in the original. Every level is open from the start, so you can look ahead before committing to anything.
- **A placement test** if you already know some Spanish — it sets you down at the right level instead of making you start at the beginning.
- **Lessons, grammar and dialogues.** Explanations in plain English, examples read aloud, and conversations worked through line by line.
- **A verb trainer** covering the tenses and moods a real course asks for, with the irregulars where they actually fall.
- **Spaced repetition** on every word and grammar point, so what you keep missing comes back and what you know does not.
- **Speaking and listening.** Read a phrase aloud and the browser's own speech recogniser scores it; listen and type what you heard.
- **Six games** — Word Hunt, Mercado, Lotería, Crucigrama, Escucha y Escribe and the gender game — all paying XP into the same pot.
- **Four companions** — Lola the axolotl, Mota the kitten, Nopalito the cactus and Nube the cloud-sheep — who grow through five stages on the XP you earn.
- **A casita** to spend quetzalitos on: outfits for your companions, furniture for the room, and chests that open on a daily streak.
- **Install it.** Tap Install in the top bar (on an iPhone: Share → Add to Home Screen) and Hablemos sits on the home screen with its own icon, opens with no browser bar and works with no connection at all.
- **Light, dark, or match your device**, in three colour schemes, behind the settings gear.

The culture, examples and place names lean Guatemalan, because that is who it was built for.

## The account

There is no sign-up wall — the app opens straight into itself and works entirely on the device.

Signing in is optional, and only does one thing: it lets you pick the app back up on another phone, or after clearing your browser, with your streak and your companions intact. A name and a password, and the same two sign you in anywhere.

## Privacy

Without an account, everything stays in your browser's own storage and clearing site data removes it.

With one, what leaves your device is: your first name, an identifier derived from your password (never the password itself), and your practice progress. It goes to a Supabase project **hosted in Canada**, owned by JohnsonXCorp, and is used only to carry your progress between devices. It is not sold, not shared, and not added to any mailing list.

## How it's built

One self-contained `index.html` — no build step to serve it, no dependencies to install, and no network calls except the web fonts and the progress sync. The companions and icons are inline SVG drawn for this app. A service worker keeps the last good copy of the page, so a new version going up never leaves you looking at an error.

Hablemos and **[Vamos](https://thepastor.github.io/vamos/)** are the same engine with different brand files — Vamos is the neutral build, and it teaches French and Japanese as well.

Built by **Johnson[X]Corp**. The version and build date sit in the footer of every page, next to *What changed*.

## Licence — this is not open source

**Copyright © 2026 JohnsonXCorp. All rights reserved.**

The repository is public so the app can be served from GitHub Pages, and so anyone can check for themselves what the page does. It is **not** published for reuse.

You may use the app, install it, read the source, and keep your own progress. You may not republish it, rehost it, redistribute it, sell it, strip its notices, or build another product out of it.

- Full terms: **[LICENSE](LICENSE)**
- Terms of use for the live app: **[TERMS.md](TERMS.md)**
- Other people's code inside the build, and their licences: **[THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md)**

GitHub's own terms let any GitHub user fork a public repository. That is a licence to fork here, and nothing more — every restriction above still applies to a fork.

To ask for permission for anything the licence does not allow, open an issue.
