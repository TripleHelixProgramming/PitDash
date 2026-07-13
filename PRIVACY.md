# Pit Dash Privacy Policy

**Effective date:** 2026-05-15

Pit Dash is a free utility built by FRC Team 2363 (Triple Helix) for
the FRC community. It is designed from the ground up to need as
little of your data as possible to be useful.

## The short version

- Pit Dash does **not** collect personal information.
- Pit Dash does **not** include any analytics, tracking, or
  advertising frameworks.
- Pit Dash has **no user accounts**. There is nothing to sign in to.
- All of your settings (team number, API keys, app preferences) live
  only on your device.
- Pit Dash talks to public competition-data services so it can show
  you match data. It does not send your identity to them.

## What data Pit Dash stores on your device

Pit Dash stores a small amount of data locally so it can remember
your configuration across launches:

- Your FRC team number.
- API keys you have entered for The Blue Alliance and FRC Nexus.
- Optional Google Spreadsheet ID and tab name for your robot's
  reference data.
- App preferences (selected event, time-display mode, source-health
  thresholds, etc.).
- A local SQLite cache of recent competition data so the app keeps
  working when your network drops.

This data is stored using your device's standard preference and
local-database APIs. It never leaves your device. There is no
Pit Dash backend that data can be uploaded to.

## What data Pit Dash sends over the network

Pit Dash makes outbound network requests to the following public
services so it can display competition data:

| Service | What it provides | Their privacy policy |
|---|---|---|
| The Blue Alliance | Match schedules, scores, rankings, team information | [thebluealliance.com/privacy](https://www.thebluealliance.com/privacy) |
| FRC Nexus | Real-time queuing, on-field status, pit maps | [frc.nexus](https://frc.nexus) |
| Statbotics | Team and match analytics (EPA, win probability) | [statbotics.io](https://www.statbotics.io) |
| Google Sheets | Optional, only if you configure a robot-reference spreadsheet | [policies.google.com/privacy](https://policies.google.com/privacy) |
| YouTube (thumbnails) | Match replay thumbnails embedded in match details | [policies.google.com/privacy](https://policies.google.com/privacy) |

These requests include only the information needed to fetch public
data (e.g., an event key, team number, or match number). They do
not include any user identifier, account name, device fingerprint,
or other identifying information beyond your IP address, which is
visible to any web service you connect to. Pit Dash does not
collect, log, or retain those IPs.

Each of those services has its own privacy policy linked above and
operates under its own terms. Pit Dash is not affiliated with The
Blue Alliance, FRC Nexus, Statbotics, Google, or YouTube.

## Permissions Pit Dash requests

Pit Dash currently requests no special device permissions on iOS or
Android beyond ordinary internet access.

## Children's privacy

FRC is a high school robotics competition, and Pit Dash may be used
by people under 13. Because Pit Dash does not collect personal
information from anyone, it does not collect personal information
from children. We do not knowingly contact or track anyone, of any
age. If you believe a child has somehow provided personal
information through Pit Dash, please contact us using the address
below so we can investigate.

## Changes to this policy

If the way Pit Dash handles data changes in a future release, this
policy will be updated and the new effective date noted at the top.
Significant changes (for example, adding any analytics or any kind
of remote logging) will also be called out in the release notes.

## Contact

For privacy questions, please open an issue on the Pit Dash GitHub
project:

<https://github.com/TripleHelixProgramming/PitDash/issues>

You may also reach Triple Helix through the team's public contact
channels at <https://team2363.org>.
