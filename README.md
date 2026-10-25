# F.O.C.U.S.© Talking Clock

**Jachbit 2026** · The Eastern Time clock of the F.O.C.U.S. Edge Scanner, on its own: one HTML file, no server, no account, no install.

## What it does
- **Eastern Time clock**: 24-hour or 12-hour, the date, six fonts (Roboto Mono, Orbitron digital, Share Tech Mono LCD, Consolas, Arial Black, Segoe UI) and sizes from 48 to 200 px. A full-screen button.
- **Market session**: PRE-MARKET / MARKET OPEN / AFTER HOURS / CLOSED with a countdown to the next change (pre-market 4:00, open 9:30, close 16:00, after hours end 20:00 ET). NYSE holidays and 1:00 PM early closes for 2026-2027 are built in; add next year's in the `HOLIDAYS` / `EARLY_CLOSE` lists in `index.html`.
- **Main clock**: Eastern (New York) by default, or your local time (e.g. Pacific, PT) or any world city (⚙ Settings → Main clock). The big clock and the date follow it, New York moves into the world clocks, and the voice leads with your zone. The market session, the countdown and "market hours only" stay on New York time, and so does the small header clock. Shortcut: the ⇄ button under the clock (also in compact mode) or the **T** key swaps the main clock between New York and your other zone (⇄ PT / ⇄ ET); the other zone is your last non-Eastern choice in Settings, else your local time.
- **World clocks**: up to 4 cities (plus New York when the main clock is not Eastern), with +1 / -1 when the day differs from the main clock.
- **Compact mode** (▭ Compact, or the **H** key): hides the header and sizes the clock, date, session and world clocks to the window, so a small window in a corner of a big screen still shows the largest clock that fits. Move the mouse over it for the ☰ Header button (or press H again) to bring the header and Settings back. Remembered next time.
- **Voice on / off**: the 🔊 / 🔇 icon under the clock (also in compact mode), the header 🔊 Talk button or the **V** key.
- **Keys**: **H** compact on / off · **V** voice on / off · **T** swap the main clock · **F** full screen on / off (the ⛶ Full button turns into ↧ Min in full screen) · **Esc** closes Settings and Help. **? Help** explains it all on the page.
- **Talking clock**: says the time every 15, 30 or 60 minutes ("It's 10:30 AM Eastern"; tick "Also say my local time" to add yours: "..., 7:30 AM Pacific"), all day, or during market hours only if you tick it, in the voice and speed you pick (the browser's built-in voices; Microsoft Edge has the most natural ones).

## Use it
1. Double-click `start.bat` (or open `index.html` in Chrome or Edge).
2. Click once anywhere on the page: browsers only let a page speak after a click.
3. Settings (⚙): font, size, time format, date, session, world clocks, talking clock, voice and speed. They are saved in this browser.

The fonts load from Google Fonts; offline, the clock falls back to the computer's own fonts and keeps working.

## Files
| File | What |
|---|---|
| `index.html` | the whole clock |
| `start.bat` | opens it in the default browser |
| `backup_all.bat` | timestamped copies into `backups\` before editing |

For personal research only, not financial advice. © 2026 Jachbit. All rights reserved. · [linktr.ee/jachbit](https://linktr.ee/jachbit)

MIT License (see `LICENSE`): adapted from the edge-scanner dashboard clock by Tape to Edge.
