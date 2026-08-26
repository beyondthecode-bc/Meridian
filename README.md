<p align="center">
  <img src="images/banner.jpg" alt="Meridian" width="100%">
</p>

<p align="center">
  <strong>Time zone coordination for remote teams</strong><br>
  See who's available, find meeting overlaps, and plan across time zones. One glance from your menu bar.
</p>

<p align="center">
  <a href="https://apps.apple.com/app/id6799510161"><img src="https://img.shields.io/itunes/v/6799510161?style=flat-square&label=Mac%20App%20Store&color=0D96F6&logo=apple&logoColor=white" alt="Current Meridian Mac App Store version"></a>
  <a href="https://github.com/beyondthecode-bc/Meridian/releases/latest"><img src="https://img.shields.io/github/v/release/beyondthecode-bc/Meridian?style=flat-square&label=Direct%20build&color=blue" alt="Latest direct release"></a>
  <a href="https://github.com/beyondthecode-bc/Meridian/stargazers"><img src="https://img.shields.io/github/stars/beyondthecode-bc/Meridian?style=flat-square" alt="Stars"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-macOS%2014%2B-lightgrey?style=flat-square&logo=apple" alt="Platform">
  <img src="https://img.shields.io/badge/chip-Apple%20Silicon%20%2B%20Intel-orange?style=flat-square&logo=apple" alt="Apple Silicon + Intel">
  <img src="https://img.shields.io/badge/swift-6.0-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift">
  <img src="https://img.shields.io/badge/SwiftUI-native-007AFF?style=flat-square&logo=swift&logoColor=white" alt="SwiftUI">
</p>

<p align="center">
  <a href="https://github.com/sponsors/beyondthecode-bc"><img src="https://img.shields.io/badge/Sponsor-%E2%9D%A4-pink?style=flat-square&logo=github" alt="GitHub Sponsors"></a>
  <a href="https://www.buymeacoffee.com/BEYONDTHECODE"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=flat-square&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee"></a>
</p>

<p align="center">
  Built with Swift and SwiftUI. No Electron, no web views, no bloat.
</p>

---

> [!NOTE]
> **This repository is the Meridian community hub** — translations, issue tracking, and direct releases. Meridian is a closed-source macOS app; the source code is not published here. Meridian is available as a paid-upfront [Mac App Store edition](https://apps.apple.com/app/id6799510161) and as a separately licensed [direct edition](https://github.com/beyondthecode-bc/Meridian/releases/latest).


## Screenshots

<p align="center">
  <img src="images/1.png" alt="Team Tab" width="420">
  &nbsp;&nbsp;
  <img src="images/2.png" alt="Planner Tab" width="420">
</p>

---

## Install and update

### Existing users

- **Mac App Store edition:** open the **App Store → Updates** to install an available update. This edition receives updates only through the Mac App Store.
- **Direct edition:** open Meridian's menu and choose **Check for Updates…**, or open **Settings → About → Check for Updates**. If the updater is unavailable or fails, download the latest direct ZIP from [GitHub Releases](https://github.com/beyondthecode-bc/Meridian/releases/latest), quit Meridian, and replace `Meridian.app` in Applications manually.

### New installations

- **Mac App Store edition — $6.99:** [buy Meridian on the Mac App Store](https://apps.apple.com/app/id6799510161). It is a paid-upfront app with no account, subscription, in-app purchase, or separate license key.
- **Direct edition — $6.99 license:** download the signed app from [GitHub Releases](https://github.com/beyondthecode-bc/Meridian/releases/latest), unzip it, and move `Meridian.app` to Applications. Buy a one-time license from [Gumroad](https://store.beyondthecode.app/l/meridian), then enter the emailed key and click **Activate**. The license works on up to three Macs at a time.

The two editions use separate update and licensing channels, so their version numbers may differ.

## Features

- **Team Roster** -- Add your team members with their time zones. See availability status at a glance: working, late hours, off, or sleeping.
- **Day Arc Visualization** -- Semicircular sun position shows where each person is in their day. Toggle between filled and outline styles.
- **Overlap Band** -- Stacked working hours at the bottom of the team view. Highlighted overlap shows when everyone (or most) are available.
- **Time Slider** -- Preview future hours with a drag slider. 30-minute snaps, shows how availability changes throughout the day.
- **Meeting Planner** -- Select participants, set duration, and filter by availability preference (all working, at least N, any overlap). Auto-ranked best slots with star indicator.
- **Calendar Integration** -- Optional Calendar.app integration shows busy times with hatching overlay in the planner. Requires calendar permission.
- **Google Meet & Microsoft Teams** -- Automatically generate meeting invites directly from the planner. Pick a time slot, choose your platform, and share.
- **Copy Formatted Times** -- One click to copy meeting times formatted for each participant's time zone. Plain text and rich text.
- **Groups** -- Organize team members into groups. Filter the team view and planner by group.
- **Desktop Widgets** -- Small, medium, and large WidgetKit widgets. Configurable per group. Shows team status, day arcs, and overlap info.
- **Menu Bar** -- Globe icon with optional live count indicator. Three display styles.
- **Notifications** -- Workday-started alerts and overlap reminders. Quiet hours suppression.
- **Themes** -- Light, dark, and system appearance. Custom accent color. Compact mode.
- **Multi-Device Licensing** -- Activate on up to 3 Macs. Self-service deactivation from Settings.

## Requirements

| | Requirement |
|---|---|
| **OS** | macOS 14.0 (Sonoma) or later |
| **Chip** | Any Mac (Apple Silicon or Intel) |
| **Price** | $6.99 one-time from the [Mac App Store](https://apps.apple.com/app/id6799510161) or [Gumroad](https://store.beyondthecode.app/l/meridian) |

## Getting Started

### 1. Install your chosen edition

Use the [Mac App Store](https://apps.apple.com/app/id6799510161), or install and activate the separately licensed direct edition using the instructions above.

### 2. Add your team

Click the **+** button to add team members. Set their name, time zone, and working hours.

## FAQ

### macOS asks for my keychain password on first launch

On first launch you may see a prompt saying *"Meridian wants to use your confidential information stored in your keychain."* This is expected -- Meridian stores an encryption key in your login keychain to protect your team data (names, time zones, working hours) with AES-256 encryption. It also stores your license key in the keychain. Click **Always Allow** so you won't be asked again.

### macOS asks to "access data from other apps"

If you enable the Calendar integration in the Meeting Planner, macOS will ask *"Meridian would like to access data from other apps."* This is required to read your Calendar.app events and show busy times in the planner. Click **Allow** to enable it. Calendar access is optional -- the app works fully without it.

## Support

- [Report an Issue](https://github.com/beyondthecode-bc/Meridian/issues)
- [Website](https://beyondthecode.app)
- [GitHub Sponsors](https://github.com/sponsors/beyondthecode-bc)
- [Buy Me a Coffee](https://www.buymeacoffee.com/BEYONDTHECODE)
