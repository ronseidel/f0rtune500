# f0rtune500

A satirical resume generator. Fill out a form, get a cleanly formatted CV full of bankrupt Fortune 500 names. Print it, share it, frame it.

No one can prove you *didn't* work at these companies.

**Live:** [f0rtune500.app](https://f0rtune500.app)

---

## What it does

You give it your name, email, location, industry, and career level. It hands back a formatted resume where every job is at a famously defunct American company — Enron, Lehman, Blockbuster, Pan Am, Borders, Toys "R" Us, Circuit City, and friends.

Dates work backward from each company's bankruptcy year. Titles ladder from Entry Level up to C-Suite. Every role comes with absurd, era-appropriate bullet points. References are unavailable for legally or biologically unfortunate reasons.

Everything runs in your browser. Nothing is sent anywhere.

---

## How to use

1. Visit [f0rtune500.app](https://f0rtune500.app).
2. Fill out the form.
3. Click **Generate resume**.
4. Click **Save as PDF** (or hit regenerate for a different combination of companies).

The browser's print dialog handles PDF export. The filename is pre-populated with your name.

---

## Tech

One HTML file. No build step, no dependencies, no analytics.

- Vanilla HTML / CSS / JS
- Fonts: Inter (body), Space Mono (brand wordmark and system metadata)
- Palette: 0fam house colors (ink green `#034D32`, accent green `#028454`)
- PDF export via native browser print
- Dark mode handled via `prefers-color-scheme`

---

## Part of 0fam

f0rtune500 is one of 100 focused micro-apps in the 0fam ecosystem. Shared brand conventions across the family:

- Zero-substitution naming (0fam, b0p, st0rm, marg0, b0ng0, f0rtune500)
- Space Mono wordmark with dotted 0s as the brand mark
- No individual app logos — the typography is the identity

More at [r0n.info](https://r0n.info).

---

## Disclaimer

This is satire. Do not submit a f0rtune500 resume to an actual job application. It will not help you get hired. It may help you entertain a group chat.

---

## Credits

Built by [Ron Seidel](https://rontheron.com).
