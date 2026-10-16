# Innovation & Valorisation Pitch Session — Judging

MCAST R&I Expo 2026 · Day 2 · Friday 30 October 2026 · 13:00–14:30 · 4 judges

**Live site:** https://nikocall.github.io/mcast-ri-expo-2026/

| Page | For | Link |
|---|---|---|
| Landing page | Everyone | https://nikocall.github.io/mcast-ri-expo-2026/ |
| Judging Scorer | Judges | https://nikocall.github.io/mcast-ri-expo-2026/scorer.html |
| Printable scorecard (A4 PDF) | Judges on paper | https://nikocall.github.io/mcast-ri-expo-2026/scorecard.pdf |
| Master Results | Organiser (master device) | https://nikocall.github.io/mcast-ri-expo-2026/results.html |

The landing page has a QR code that opens the scorer.

## How it works

1. The organiser keeps **Master Results** open on their own device and browser — that copy is the master.
2. Judges open the scorer (link or QR) and score every pitch 1–5 on four criteria; scores save in their own browser.
3. Each judge taps **Send to organiser**, which makes a link (and QR) holding their marks, and shares it (WhatsApp, email…).
4. The organiser opens each link on the master device and taps **Add to master results**. Links can also be pasted in; CSV import and typing in paper scorecards still work.

## Scoring

- Four criteria, 25% each: Originality & Research Merit · Clarity of Impact Pathway · Feasibility & Partnerships · Delivery & Communication.
- **Best Research Impact:** highest average on criteria 1 + 2. **Most Valorisation Potential:** highest average on criterion 3. **People's Choice:** audience vote, not scored here.
- **Tie-break:** award score (or total) → higher total → higher criterion 2 (Clarity of Impact Pathway) → panel decides.

## Privacy

Every page is a static file. Scores are never uploaded; they stay in each person's browser (localStorage) until downloaded as CSV or cleared. A judge's "Send to organiser" link carries the marks in the `#` fragment, which browsers never send to a server (GitHub included). The QR library (qrcode-generator 1.4.4) loads from cdnjs.
