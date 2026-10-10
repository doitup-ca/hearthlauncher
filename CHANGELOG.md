# Changelog

Notable changes to Hearth, newest first. Hearth is in closed testing, and these are the
builds closed testers receive.

## 0.3.1 (16) — 2026-10-10

**Fixed**
- Camera pictures on room cards refresh every 2 seconds, not every 10.
- Focused app banners on the dock and in the quick menu stay sharp.
- One press of BACK closes the notice before the Home Assistant dashboard.

**Changed**
- After pairing, "You're connected!" counts your rooms and cameras before the tour.
- Cards and the dock on the home screen are lighter, so more of the background shows through.

## 0.3.0 (15) — 2026-10-08

**New**
- A new design across all of Hearth, with four themes and a new picture daily.
- A new home screen: a bigger player, rooms, cameras, the forecast and your calendar.
- New House, Media and Climate tabs.
- The top bar has a gear for Settings and a bell for notifications.
- Hold OK anywhere for a quick menu.
- A new overlay on full-screen TV.
- A new first-run setup and tour.

**Changed**
- Dawn, Day, Dusk and Night replace Ember, Midnight and Signal.
- Live TV plays more steadily, and you can choose TS or HLS.

## 0.2.5 (14) — 2026-10-04

**Fixed**
- Tabs move one step per press, even while Hearth is busy.
- After an update, the remote works without pressing Home.
- The guide's shelf shows every group you've switched on.

**Changed**
- Live TV on the home screen uses far less processing power.
- Channels with no schedule show "No schedule" blocks in the guide.
- New look for the unencrypted provider warning.
- Focused tabs fill with the accent color; Midnight has new colors.

## 0.2.4 (13) — 2026-09-28

**Security**
- Whole-house lights need a second press in the quick menu.
- Android's system log no longer records passwords or your Home Assistant address.
- Voice search stops if you switch apps mid-search.

**Fixed**
- Turning the TV on opens Hearth, not the Google home screen.
- Live TV recovers by itself after a network drop.
- A failed guide update keeps the old guide.
- A camera that can't stream shows snapshots.
- Lock status shows Jammed instead of Unlocked.

**Changed**
- The smallest display size was removed.

## 0.2.3 (12) — 2026-09-25

**Security**
- Pop-ups no longer appear over other apps once the accessibility service is off.
- Hearth takes over as your launcher only when you've switched that on.
- Other apps can no longer open your Home Assistant dashboard in Hearth.
- Removed a leftover diagnostic file from the device.

**Fixed**
- Home Assistant pop-ups work straight after pairing, without a restart.
- Newly installed apps appear in the dock straight away.

## 0.2.2 (11) — 2026-09-25

**Security**
- Stream and logo redirects are checked, and insecure ones are upgraded.
- Pairing sends your token only inside your home network.
- Re-pairing Home Assistant no longer leaves an old connection open.

**Improved**
- A channel Hearth can't play safely now says why.
- Settings says when Home Assistant refuses a camera or calendar.
- The accessibility description names all of its uses.

**Fixed**
- A jammed or open lock no longer shows as locked.
- If saved settings are lost, Hearth now tells you on screen.

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

First build for closed testers. This is what it could do.

**Included**
- Hearth replaces your TV's home screen, with a dock of apps you choose and order.
- Hold OK anywhere, even over video, for the guide, apps, settings and lights.
- Your Home Assistant house on screen: rooms, lights, cameras, security and weather.
- Locks, alarms and garage doors are shown, never controlled.
- Pair Home Assistant from your phone, with nothing typed on the TV.
- Your Home Assistant dashboard inside Hearth, view-only.
- Home Assistant automations can put a card over whatever is playing.
- Live TV from your own provider, with a guide, favourites, groups and voice search.
- A demo house to try without Home Assistant, and every part can be switched off.
- Three themes, and a display scale for reading across the room.
