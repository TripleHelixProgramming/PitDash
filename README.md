<table>
<tr>
<td width="180" valign="top" align="center">
  <img src="assets/icon.png" alt="Pit Dash icon" width="140"><br>
  <h1>Pit Dash</h1>
</td>
<td valign="top">

Pit Dash is a match-day companion for FRC teams. It shows your next-match countdown, alliance partners and opponents, live queuing status, win probabilities, event rankings, the pit map, and the rest of the schedule — on a phone or a tablet, with multi-pane layouts when you have the screen for it.

**iPhone / iPad:** The iOS version is available via Apple [App Store](https://apps.apple.com/us/app/pit-dash/id6761343496).

**Android:** Android installation instructions are below.

If you encounter any issues or have suggestions for improvement, please create a new [Issue](../../issues).

</td>
</tr>
</table>

## Screenshots

<p align="center">
  <a href="docs/screenshots/pit.md"><img src="assets/screenshots/pit.png" alt="Pit view" width="200"></a>
  &nbsp;
  <a href="docs/screenshots/teams.md"><img src="assets/screenshots/teams.png" alt="Teams and rankings" width="200"></a>
  &nbsp;
  <a href="docs/screenshots/schedule.md"><img src="assets/screenshots/schedule.png" alt="Schedule" width="200"></a>
  &nbsp;
  <a href="docs/screenshots/teamdetail.md"><img src="assets/screenshots/teamdetail.png" alt="Team detail" width="200"></a>
  &nbsp;
  <a href="docs/screenshots/robot.md"><img src="assets/screenshots/robot.png" alt="Robot" width="200"></a>
  &nbsp;
  <a href="docs/screenshots/pitmap.md"><img src="assets/screenshots/pitmap.png" alt="Pit map" width="200"></a>
</p>

<p align="center"><sub>Tap any screenshot for a description and full-resolution view.</sub></p>

## What you get

- **Pit screen** — match countdown, alliance cards for partners and opponents, Nexus queuing banners (`QUEUING SOON` → `NOW QUEUING` → `ON DECK` → `ON FIELD`), and a Statbotics win-probability bar for the upcoming match.
- **Schedule** — qualifications, playoffs, and finals; filter to just your team's matches or browse the whole event, including matches already played.
- **Teams & rankings** — live event rankings with W-L-T, RP average, average score, and Statbotics EPA broken out by Auto / Teleop / Endgame.
- **Team detail** — match history, OPR/DPR/CCWM, awards, and YouTube links for each match. Reachable from any team card, ranking row, pit-map cell, or schedule entry.
- **Pit map** — interactive, pinch-to-zoom map of the venue with your team and your upcoming-match opponents highlighted.
- **Robot tab** — pulls a Google Sheet your team controls (wiring, setpoints, auto routines, pit-crew checklists — whatever's useful) and renders each section as its own collapsible tile.
- **Tablet layouts** — on iPad and larger Android tablets, multiple views can be shown side-by-side.
- **Off-season / between events** — when you're not at a live event the app shows season EPA, W-L record, and per-event results.

## Screenshot gallery

A cross-section of how information is presented on phone and tablet.

### iPhone

<p align="center">
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPhone%2017%20Pro%20Max%20-%202026-05-15%20at%2016.24.00.png" alt="iPhone — pit view" width="180">
  &nbsp;
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPhone%2017%20Pro%20Max%20-%202026-05-15%20at%2016.25.19.png" alt="iPhone — schedule" width="180">
  &nbsp;
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPhone%2017%20Pro%20Max%20-%202026-05-15%20at%2016.26.03.png" alt="iPhone — teams and rankings" width="180">
  &nbsp;
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPhone%2017%20Pro%20Max%20-%202026-05-15%20at%2016.28.55.png" alt="iPhone screenshot" width="180">
</p>
<p align="center">
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPhone%2017%20Pro%20Max%20-%202026-05-15%20at%2016.33.29.png" alt="iPhone — team detail" width="180">
  &nbsp;
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPhone%2017%20Pro%20Max%20-%202026-05-15%20at%2016.34.28.png" alt="iPhone — pit map" width="180">
  &nbsp;
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPhone%2017%20Pro%20Max%20-%202026-05-15%20at%2016.38.08.png" alt="iPhone — robot" width="180">
  &nbsp;
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPhone%2017%20Pro%20Max%20-%202026-05-15%20at%2016.38.59.png" alt="iPhone screenshot" width="180">
</p>

### iPad

<p align="center">
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPad%20Pro%2013-inch%20%28M5%29%20-%202026-05-15%20at%2016.43.18.png" alt="iPad — multi-pane layout" width="320">
  &nbsp;
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPad%20Pro%2013-inch%20%28M5%29%20-%202026-05-15%20at%2016.43.41.png" alt="iPad — multi-pane layout" width="320">
  &nbsp;
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPad%20Pro%2013-inch%20%28M5%29%20-%202026-05-15%20at%2016.44.43.png" alt="iPad — multi-pane layout" width="320">
</p>
<p align="center">
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPad%20Pro%2013-inch%20%28M5%29%20-%202026-05-15%20at%2016.45.43.png" alt="iPad — multi-pane layout" width="320">
  &nbsp;
  <img src="assets/screenshots/Simulator%20Screenshot%20-%20iPad%20Pro%2013-inch%20%28M5%29%20-%202026-05-15%20at%2016.48.36.png" alt="iPad — multi-pane layout" width="320">
</p>

## Installing

1. Go to the [Releases](../../releases) page and download the latest `.apk` file onto your Android device
2. Open the file from Downloads or the notification tray
3. When prompted about unknown sources, tap **Settings** and enable "Allow from this source"
4. Go back and tap **Install**

Android requires this "unknown sources" step for any app that didn't come from the Play Store. You can turn the setting back off after installing.

If your device blocks the install entirely, go to **Settings → Apps → Special access → Install unknown apps** and enable it for Chrome or whichever app you're opening the file from.

## Setup

The app walks you through initial configuration. You'll need a team number and a TBA API key (free at [thebluealliance.com/account](https://www.thebluealliance.com/account)).

A Nexus API key (free at [frc.nexus](https://frc.nexus)) is also recommended. Most events have a Nexus volunteer running Field Monitor, which gives the app real-time field timing and queuing banners (QUEUING SOON → NOW QUEUING → ON DECK → ON FIELD). The countdown is significantly more accurate with Nexus data.

Statbotics data (EPA, win probabilities) is pulled automatically with no key required. The Robot tab is optional and points at a public Google Sheet your team owns.

The app auto-detects your event based on the date. The More menu (bottom right) lets you switch events manually.

## Limitations

- **No auto-update on Android.** Check the [Releases](../../releases) page for new builds. You'll need to download and reinstall manually.
- **Android polish is in progress.** Some rough edges are expected.
