# Changelog

Notable changes to Hearth, newest first. Hearth is in closed testing, and these are the
builds closed testers receive.

## 0.2.0 (7) — 2026-09-16

**Added**
- **Plain M3U playlists.** As well as a provider account, Hearth now takes a playlist address
  directly, with channels, logos and groups from the playlist itself. Hearth still doesn't
  include any channels or subscriptions.
- **A separate TV guide.** A playlist's own guide address is used automatically, and you can
  type a different one if your guide comes from somewhere else. Gzipped guides are supported;
  tar archives are not yet.
- If saved settings ever can't be read and have to be reset, Hearth now tells you on the home
  screen instead of quietly looking like a fresh install.

**Improved**
- Playlists and guides are **HTTPS only**. A playlist names hundreds of hosts you have never
  seen, so unencrypted playlists, guides and channels are refused rather than asked about.
  Some channels on public playlists will not appear for this reason.
- The Favourites view no longer suggests your provider is at fault when you simply haven't
  starred anything yet.
- Disconnecting a provider leaves the remote in Settings, where you were.

**Fixed**
- Changing to a different provider now clears the channels, favourites, groups, watch history
  and guide that belonged to the old one. Re-entering a rotated password for the **same**
  provider keeps all of it, as before.
- Switching accounts no longer leaves the previous provider's channel groups on screen.
- The guide opens on the current time rather than where the grid happened to be scrolled.
- Damaged saved settings can no longer stop Hearth from starting.

## 0.1.4 (6) — 2026-09-14

**Added**
- Smoke, CO and heat detectors appear on the Security card, the Security tab and the
  home screen's status. An active alarm is shown first, ahead of an armed alarm panel.
  Detectors that are unavailable in Home Assistant are left out.
- The Climate tab now lists your thermostats in full, and the Home card shows every
  thermostat with its humidity.
- The Climate and Security cards can be hidden or moved, from Settings ▸ Home Assistant ▸
  Cards or from the card's own panel.

**Improved**
- Tiles stay sharp and bright when you select them.
- A card's panel keeps the remote inside it while it is open, and closing it returns you to
  the card.
- From the main picture, UP goes to the Home tab and RIGHT goes to the camera beside it. From
  the last tab in the header, RIGHT moves down into the page.

**Fixed**
- The focus ring on the first card in a list is no longer cut off.
- A case where live TV could start in the background after you left Hearth.

## 0.1.3 (4) — 2026-09-11

**Improved**
- App tiles on the dock and camera feeds are noticeably sharper.
- Dock tiles are now a standard 16:9 shape, so app artwork is no longer cropped at the top
  and bottom.

**Fixed**
- The top row of tiles on a tab no longer cuts off the focus ring.

## 0.1.2 (3) — 2026-09-10

**Fixed**
- Holding OK no longer closes Hearth when an app on your dock has the same name as one of
  Hearth's own shortcuts. The Android Settings app was the usual cause.

**Security**
- The dashboard stays on your Home Assistant server. A card or link that tries to open
  another website in its place is blocked.

## 0.1.1 (2) — 2026-09-08

**Added**
- Settings ▸ Accessibility Service explains Hearth's optional accessibility service, which
  lets Hearth come back to the front when another launcher takes the screen and lets Sleep in
  the dock turn the screen off. It sees only which app comes to the front, cannot read what is
  on screen, and stores and sends nothing. Hearth works without it, and the screen opens
  Android's setting to turn it on or off.

## 0.1.0 (1) — 2026-09-07

First build for closed testers: a launcher for Android TV that opens on your Home Assistant
house (rooms, cameras, climate and security) with a built-in live TV player and a dock of your
apps.
