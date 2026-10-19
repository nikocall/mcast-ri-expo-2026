# Innovation & Valorisation Pitch Session — Live Judging

MCAST R&I Expo 2026 · Day 2 · Friday 30 October 2026 · 13:00–14:30

**Live page:** https://nikocall.github.io/mcast-ri-expo-2026/

One page for everyone, with a **Master** tab for the organiser and one tab per judge.

## How it works

1. **Organiser** opens the page and taps **Create judging event**. That device becomes the master.
2. On the Master tab: add the teams, set the number of judges (that many judge tabs appear), name them.
3. Share the judges' link or QR code shown on the Master tab.
4. Each **judge** opens the link, taps their name, confirms, and marks every team 1–5 (with notes). Marks save instantly and the tab locks to their device.
5. The Master tab shows live results: award leaders, ranking, per-judge totals, notes. The organiser can view and edit every tab (e.g. to type in a paper scorecard), unlock a tab if a judge changes device, and let judges see results with a switch.
6. The **organiser key** on the Master tab opens the master on a second device.

## Scoring

- Four criteria, 25% each: Originality & Research Merit · Clarity of Impact Pathway · Feasibility & Partnerships · Delivery & Communication.
- **Best Research Impact:** highest average on criteria 1 + 2. **Most Valorisation Potential:** highest average on criterion 3. **People's Choice:** audience vote, not scored here.
- **Tie-break:** award score (or total) → higher average total → higher average on criterion 2 → panel decides.

## Files

| File | What |
|---|---|
| `index.html` | Live judging page (Firebase Firestore + anonymous sign-in) |
| `firestore.rules` | Security rules published to the Firebase project: only organisers edit teams/judges; each judge tab is writable only by the device that claimed it (or an organiser) |
| `scorecard.pdf` | Printable A4 scorecard |
| `scorer.html`, `results.html` | Offline backup (no server): judge scorer + master results via "Send to organiser" links |

The Firebase web config in `index.html` is public by design; access is enforced by `firestore.rules`.
