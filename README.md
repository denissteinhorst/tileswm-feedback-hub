<table>
<tr>
<td>
  <img src="assets/icon.png" alt="TilesWM Icon" width="120">
</td>
<td>
  <h1>TilesWM Feedback Hub</h1>
  <p>Thanks for using TilesWM. I am the solo developer behind the project, and thoughtful feedback lets me keep the app precise, efficient, and aligned with the macOS experience you expect.</p>
</td>
</tr>
</table>

---

## How to share feedback

- **Report a bug** -> open a new issue and paste [`templates/bug-report.md`](templates/bug-report.md)
- **Suggest a feature** -> open a new issue and paste [`templates/feature-request.md`](templates/feature-request.md)
- **Ask a question** -> start a discussion with [`templates/question.md`](templates/question.md)

Each template mirrors how TilesWM is structured - profiles, monitors, utility keys, and debug tooling - so I can triage quickly and keep context straight.

---

## Must-haves before you file

### Prerequisites

- Skim the [TilesWM.app FAQ](https://www.tileswm.app) to see if I have already covered your topic
- Search the existing GitHub issues and add your details to an open thread when the behavior matches what you see

### About the issue

- Reproduce the behavior on the latest release (see Settings > About for the build number)
- Write the exact steps you follow, in order, without skipping any gestures or key chords
- Confirm TilesWM still has Accessibility permission in System Settings > Privacy & Security
- Export the latest debug log (Settings > Debug > Export Log) right after the issue occurs
- Attach any affected profile JSON or screenshots that show your monitor layout

---

## Diagnostics I rely on

- Debug console export: `Settings > Debug > Export Log`
- Profiles: `Settings > Backup > Export Backup`
- Database "if corrupted": `~/Library/Application Support/dev.steinhorst.tileswm/tileswm.sqlite3`
- Screen recordings: QuickTime with the cursor visible makes tile issues obvious
- Hardware state: note your Mac model, chip, and any connected hubs or docks

If you are reporting window placement glitches, mention whether Stage Manager, Spaces, or third-party window tools are running. For input issues, include the mouse or keyboard vendor and layout.

---

## Privacy and security

This repository is public. Do not include personal data, work content, or anything you are not comfortable sharing. Sanitize logs before attaching if they contain sensitive window titles.

---

## What happens after you submit

I review every report, group related issues, and respond once I have a clear next step or need more detail. High-impact bugs and regressions ship first, followed by quality-of-life improvements. Feature requests are evaluated against performance impact, accessibility expectations, and how they fit TilesWM’s core: fast, explicit tiling on macOS.

Thank you for helping me push TilesWM forward.
