<div align="center">

![SENTRY — AI Cargo Intelligence](assets/banner.svg)

# 🛡️ SENTRY — AI Cargo Intelligence Platform

**Turn scanner images, customs paperwork, and watchlist data into one clear risk score per shipment.**

🏆 *Winner — AI Automation Excellence Award, WEL.X AI Accelerator 2026*

[**▶ Live demo**](https://ebinraj2007-cmd.github.io/sentry/) · [Report a bug](https://github.com/ebinraj2007-cmd/sentry/issues) · [Contact](mailto:ebinraj2007@gmail.com)

</div>

---

## The problem

Customs officers cross-reference every shipment by hand — scanner image here, declaration form there, watchlist in a third window. It's slow, it's easy to miss things, and it doesn't scale. A single shipment can eat **20+ minutes** of manual checking.

## What SENTRY does

SENTRY pulls all three sources into one screen and fuses them into a single **0–100 risk score**, so an officer can see *at a glance* which shipments need a closer look and which are clear. What took 20 minutes takes a few seconds.

## Demo

<!-- ▶ RECORD A 10–15s GIF OF THE LIVE DEMO AND DROP IT HERE:  ![SENTRY demo](assets/demo.gif)  -->
> **Live demo:** https://ebinraj2007-cmd.github.io/sentry/
>
> *(A short screen recording goes here — see “Add the demo GIF” at the bottom of this file.)*

## Features

- **Risk fusion engine** — combines scanner imagery, customs declarations, and watchlist hits into one weighted 0–100 score.
- **Instant triage** — shipments sort by risk so the highest-priority ones surface first.
- **Explainable** — every score shows *why* it landed where it did, not just a number.
- **Live, interactive demo** — runs entirely in the browser, no install, hosted on GitHub Pages.
- **Built in 48 hours** — designed, built, and shipped during a two-day AI accelerator.

## How it works

```
scanner image  ─┐
customs form    ├──►  fusion engine  ──►  0–100 risk score  ──►  triage view
watchlist data ─┘        (weighted rules)                         (sorted by risk)
```

## Tech stack

JavaScript · HTML · CSS · client-side risk-fusion logic · GitHub Pages

## Run it locally

```bash
git clone https://github.com/ebinraj2007-cmd/sentry.git
cd sentry
# it's a static site — open index.html, or serve it:
python3 -m http.server 8000
# then open http://127.0.0.1:8000
```

## The award

SENTRY was submitted as a capstone at the **WEL.X AI Accelerator 2026** and won the **AI Automation Excellence Award** — recognised for innovation, technical execution, and using AI automation to solve a real operational problem. The award also included selection for the Summer Internship Career Day alongside employers including Emirates, Emirates NBD, Dubai Airports, Coca-Cola, and dubizzle.

## Add the demo GIF (30 seconds)

A moving demo makes this README 10× more convincing. To add one:

1. Open the [live demo](https://ebinraj2007-cmd.github.io/sentry/).
2. Record a 10–15 second clip of you running a shipment through it:
   - **Mac:** `Cmd + Shift + 5` → record a region → stop → you get a `.mov`.
   - Convert to GIF free at [ezgif.com/video-to-gif](https://ezgif.com/video-to-gif) (or [gifski](https://gif.ski)).
3. Save it as `assets/demo.gif` in this repo.
4. In this README, uncomment the image line in the **Demo** section:
   `![SENTRY demo](assets/demo.gif)`
5. Commit and push. GitHub shows it automatically.

## Author

**Ebin Raj** — [GitHub](https://github.com/ebinraj2007-cmd) · [LinkedIn](https://linkedin.com/in/ebinraj2007) · ebinraj2007@gmail.com

## License

MIT
