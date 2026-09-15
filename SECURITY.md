# Security

Thank you for looking. Hearth runs on a television in a shared room and talks to people's homes,
so security reports are taken seriously.

## Reporting a vulnerability

⛔ **Please do not open a public issue for a security problem.**

Use GitHub's private vulnerability reporting:

**→ [Report a vulnerability](../../security/advisories/new)**

The report is visible only to you and the people who maintain Hearth until it is resolved. It needs a GitHub
account, which is free — that is deliberately the only route, so nothing sensitive lands somewhere
public by accident.

**What helps:** what you were able to do, the steps to reproduce it, the app version, your device
and Android version, and whether Home Assistant and Live TV were set up.

⚠️ **Redact your own details.** A report describing your setup can carry local IP addresses, access
tokens and the entity ids that describe your home. Replace them — a report is just as useful with
`192.168.x.x` and `<token>` in it.

## What to expect

Hearth is maintained by one person, so this is a promise about honesty rather than speed:

- **An acknowledgement**, so you know it arrived and was read.
- **A plain answer** on whether it is in scope and what is being done about it.
- **Credit when it is fixed**, in the advisory and the changelog, unless you would rather not be
  named.

If you do not hear back, please chase it in the same private thread.

## Scope

Hearth is an Android TV app. **There is no Hearth account, no Hearth server, and no Hearth
backend** — the app talks to your Home Assistant and, if you set it up, your Live TV provider.
Credentials are held on the device.

**In scope**

- Anything that lets the app act on a house beyond what it is meant to touch, or that gets around
  the restrictions it advertises
- Exposure of credentials held on the device, or of them leaving it
- Anything that lets another app on the device read Hearth's data or drive its interface
- Interception or tampering with what Hearth sends over the network

**Out of scope**

- Your own Home Assistant instance, or your provider's servers — report those to them
- Attacks that need physical access to an unlocked device, or developer options the owner turned
  on themselves
- Anything about what can be watched, which Hearth has nothing to do with
- This repository's documentation and links

## A note on what Hearth deliberately does not do

Hearth can see the whole house and acts on lights, climate, fans and switches only. Everything
else — locks, alarm panels, covers, garage doors, scripts and scenes among them — is refused at
the point the app would call Home Assistant, so the refusal covers every part of the app rather
than each screen separately.

**If you find a way around that, it is exactly the report worth making.**
