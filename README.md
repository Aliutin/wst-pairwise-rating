# WST Pairwise Rating Game

**Live site: https://aliutin.github.io/wst-pairwise-rating/**

Thanks for helping rate problems related to Uzbekistan's water-saving technology (drip irrigation) program.

## How to use

**Easiest: just open the live site link above** — no download needed.

Or, run it locally:

1. Clone or download this repo (green "Code" button → "Download ZIP").
2. **Double-click `index.html`** to open it in your browser.
   - Works on Windows, macOS, and Linux. Any modern browser (Chrome, Firefox, Safari, Edge).
   - On macOS: if double-click does not work, right-click → *Open With* → *Chrome* (or another browser).
2. **Type your name or initials** on the welcome screen and press *Start rating*.
3. **Rate each pair** that appears, on three criteria in sequence:
   - **Observability** — Which is harder for the central government to see in official channels?
   - **Solvability** — Which is harder for the government to actually solve?
   - **Donor accountability** — If left unsolved, which would risk more donor consequences (frozen disbursements, conditionality, reputational cost)?
   - Click the **left card**, the **right card**, or **TIE / Equal**. Or use the keyboard: **←** , **→**, or **=**.
   - Click **← Back (undo)** to revise the previous comparison. Backspace also works.
4. After all three criteria are done, you'll see a summary table.
5. **Click "Download results JSON"** and send the downloaded file (`ratings_<yourname>_<timestamp>.json`) back to Lutfullo.

## How long does it take?

About **30–60 minutes** total. The game adapts to your answers and stops asking when your ranking stabilizes — typically 25–60 pairs per criterion.

## Tips

- Read each card carefully: definition + Telegram quote (orange) + news quote (blue), with English translations underneath the originals.
- There are **no right answers** — the rating measures *your* perspective. Make your best judgment.
- **TIE** is fine when you genuinely can't decide. It doesn't slow you down.
- **Pause anytime** — your progress is autosaved every comparison. Closing the tab and reopening shows a "Resume?" prompt.

## Privacy

Everything is stored locally in your browser. Nothing is uploaded anywhere. You only share data when you click *Download results JSON* and send the file back manually.

## Troubleshooting

- **The page is blank.** Try a different browser. If it still doesn't work, open the browser DevTools console (F12 on Windows, ⌥⌘I on macOS) and send the error message to Lutfullo.
- **You want to start over.** On the summary screen at the end, click *Restart session (wipe localStorage)*. Mid-session you can also press F12 → Console tab → run `localStorage.clear(); location.reload();`.
- **Lost your progress.** localStorage is per-browser. If you close the browser without downloading and someone else opens the file in a fresh browser, the previous session is gone. Always download before closing if unsure.
