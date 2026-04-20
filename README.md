# f0rtune500

A satirical resume generator. Fill out a form, get a cleanly formatted resume full of bankrupt Fortune 500 companies.

Live at [f0rtune500.app](https://f0rtune500.app).

## The joke

No one can prove you didn't work at these companies. They don't exist anymore.

Enron collapsed in 2001. Toys "R" Us liquidated in 2018. Sears is mostly a memory. Lehman, Blockbuster, Circuit City, Radio Shack, Compaq, Washington Mutual — all defunct, all once household names. f0rtune500 takes your form input (name, location, industry, career level) and generates a reverse-chronological resume using era-appropriate roles at companies that were real, important, and are now gone.

## The point

The output reads exactly like a real executive resume — same confident bullet points, same industry jargon, same self-important cadence. Which is kind of the joke. LinkedIn theater is interchangeable. When the company is gone and only the resume bullets remain, you start to notice how little the bullets actually said.

## Stack

- Single static HTML file
- Zero backend. Everything runs in your browser.
- 8 industries × 6–8 companies each, each with researched bankruptcy year and era-appropriate bullet library
- 5 career ladders (IC, Senior, Manager, Director, Executive) with role-appropriate titles per industry
- Reverse-chronological date logic, capped at each company's bankruptcy year, gaps closed for continuous employment
- PDF export via browser print (document.title gets rewritten on submit so the default filename includes your name)
- Dark mode support

## Privacy

Nothing is sent anywhere. No analytics, no tracking, no server. Open devtools if you don't believe me.

## Part of 0fam

f0rtune500 is part of [0fam](https://0utput.co), a family of small, focused web apps. Every name drops a letter for a zero.

## License

MIT.

## Contact

Built by [Ron Seidel](https://rontheron.com) · [hello@0utput.co](mailto:hello@0utput.co)
