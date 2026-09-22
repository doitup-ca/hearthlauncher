# Changelog

Notable changes to Hearth, newest first. Hearth is in closed testing, and these are the
builds closed testers receive.

## 0.2.1 (9) — 2026-09-22

**Added**
- Release notes now appear in Settings ▸ About.

**Improved**
- Hearth takes the screen at startup, and no longer interrupts an app you opened first.
- Hearth starts faster, and channel logos are sharper.
- Home Assistant pairing stays on your own network. Every connection step is
  checked, so some channels may stop working.

**Fixed**
- Live TV resumes from live, not where you left it.
- Hiding an area or section keeps the remote on the next card.
- Damaged settings are retried before anything is cleared.

## 0.2.0 (7) — 2026-09-16

**Added**
- **M3U playlists.** Use a playlist address instead of a provider account. Hearth still
  doesn't include any channels.
- **A separate TV guide.** Uses the playlist's own guide, or one you type in.
- If saved settings ever have to be reset, the home screen now says so.

**Improved**
- Playlists and guides must use HTTPS. Some channels on public playlists won't appear.
- Favourites no longer blames your provider when you haven't starred anything yet.
- Disconnecting a provider keeps you in Settings.

**Fixed**
- Switching providers clears the old one's channels, favourites, groups, history and guide.
  A new password for the same provider keeps them.
- The guide opens on the current time.
- Damaged saved settings can no longer stop Hearth from starting.

## 0.1.4 (6) — 2026-09-14

**Added**
- Smoke, CO and heat detectors on the Security card and tab. An active alarm shows first.
- The Climate tab lists every thermostat, with humidity.
- Hide or move the Climate and Security cards from Settings ▸ Home Assistant ▸ Cards.

**Improved**
- Tiles stay sharp when selected.
- A card's panel keeps the remote inside it, and closing it returns you to the card.
- Easier moves around the home screen with the remote.

**Fixed**
- The first card's focus ring is no longer cut off.
- Live TV could start in the background after you left Hearth.

## 0.1.3 (4) — 2026-09-11

**Improved**
- Sharper app tiles and camera feeds.
- App artwork is no longer cropped on the dock.

**Fixed**
- The top row of tiles no longer cuts off the focus ring.

## 0.1.2 (3) — 2026-09-10

**Fixed**
- Holding OK no longer closes Hearth when a dock app shares a name with one of Hearth's
  shortcuts.

**Security**
- The dashboard can't be replaced by another website.

## 0.1.1 (2) — 2026-09-08

**Added**
- Settings ▸ Accessibility Service explains the optional service that brings Hearth back to
  the front and lets Sleep turn the screen off. It sees only which app is in front, and
  stores and sends nothing.

## 0.1.0 (1) — 2026-09-07

First build for closed testers: a launcher for Android TV with your Home Assistant house, a
live TV player and a dock of your apps.
