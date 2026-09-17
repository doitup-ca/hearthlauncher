# Hearth

**One home screen for your apps, your live TV and your home.**

[Issues](../../issues) · [Discussions](../../discussions) · [Changelog](CHANGELOG.md) ·
[hearthlauncher.com](https://hearthlauncher.com) · [Privacy](https://doitup-ca.github.io/privacy/)

---

Hearth is a launcher for Android TV. It puts your apps, your live TV and, if you run Home
Assistant, your whole house on one screen built for the remote. Every part is optional: use what
you want and switch off the rest.

It is not affiliated with, endorsed by, or sponsored by Home Assistant, Nabu Casa, NVIDIA or Google.

## What it does

**Made for a remote.** Built for the D-pad, with no cursor and no touch assumptions. Hold OK
anywhere — including over full-screen video — for the guide, your apps, settings and, with
Home Assistant, your lights.
Three themes, and a display scale that grows type and layout together for across-the-room
reading.

**Live TV, if you want it.** Sign in to your own live TV provider, or point Hearth at a playlist
address, for a guide, favourites, channel groups and search, playing right on the home screen.
Playlists and guides must be encrypted (HTTPS). Hearth doesn't include any channels or
subscriptions. Or skip it entirely and never see it again.

**Your house, on the television.** Rooms come from your own Home Assistant areas, so the layout is
the one you already maintain — nothing to configure twice — and it updates as things happen.
Hide, reorder and restore rooms in place, without leaving the screen.

**Your dashboard, inside the launcher.** Hearth can show your Home Assistant dashboard right in the
launcher. Pick it by name in Settings — there is no second login. It is view-only: the remote
scrolls it, and nothing else reaches the page.

**Cameras on the home screen.** Your cameras fill a 16:9 panel, with a strip beside it when you
have more than one, and their snapshots are kept current.

**A house that says something.** A Home Assistant automation can put a card on the screen over
whatever is playing, and it clears itself.

**No Home Assistant yet?** Try the demo house — twenty-eight entities across six areas drive the
real interface, and the lights genuinely toggle. Or skip setup and use Hearth as a launcher for
your apps and live TV.

## Look, don't touch

**Hearth can see your whole house. It acts on lights, climate, fans and switches, and nothing else.**

Everything else — locks, alarm panels, covers, garage doors, scripts and scenes among them — is
shown and **refused**, in either direction: not hidden, not behind a confirmation. The refusal
happens when a command would be sent to Home Assistant, so it covers every part of the app rather
than being something each new screen has to remember.

This is a decision about televisions, not about smart locks. A TV remote is the least-guarded
thing in the house: guests, children and visitors all have it, and none of them are
authenticated. A mis-aimed press should not be able to unlock a door or arm an alarm. Your phone
can ask who you are; a remote on the sofa cannot — so the lock stays where a phone can reach it.

**Your credentials stay on your device.** Your Home Assistant access and your live TV details are
stored encrypted on the TV box, and neither is built into the app. There is no account, and
Hearth has no server.

→ [Privacy policy](https://doitup-ca.github.io/privacy/)

## Status

**Hearth is in closed testing and is not on Google Play yet** — coming to Google Play. There is no
public download at the moment.

It is developed on NVIDIA Shield hardware and tested on the NVIDIA Shield TV (2017) and Shield TV
Pro (2019), Chromecast with Google TV, and the Google TV Streamer.

## Reporting a problem

Bugs go in the [issue tracker](../../issues/new/choose); questions and ideas go in
[Discussions](../../discussions).

⚠️ **This tracker is public.** Logs and Home Assistant details routinely carry local IP addresses,
access tokens and the entity ids and area names that describe your home. Please redact before you
paste — see [CONTRIBUTING.md](CONTRIBUTING.md).

Security problems should not be filed as issues: see [SECURITY.md](SECURITY.md).

## This repository

Hearth is currently closed source. This repository is its public front door — the overview, the
changelog and the issue tracker. Issues about the app are tracked here and fixed in a private
repository; your issue stays here and gets answered here. [CONTRIBUTING.md](CONTRIBUTING.md)
explains how that works.
