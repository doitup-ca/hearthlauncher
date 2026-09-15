# Contributing

Thanks for taking the time. This repository is the **front door** for Hearth — the overview, the
changelog, and the issue tracker. Hearth is currently closed source, so the app's code is not here.

## Where to put what

| | |
|---|---|
| Something behaves incorrectly | [Open an issue](../../issues/new/choose) |
| A question, or an idea for a feature | [Discussions](../../discussions) — not an issue |
| A security problem | **Not a public issue.** See [SECURITY.md](SECURITY.md) |

Blank issues are turned off on purpose. The form asks which device you're on, which Android
version, and whether Home Assistant and Live TV are set up — those five answers are usually the
difference between a report that can be acted on and one that can't. Android TV devices differ
enough that "it doesn't work" is genuinely not actionable without them.

## Before you file

**Search the existing issues first**, including closed ones. A comment on an existing report is
worth more than a new one.

**Say what you expected and what you got.** A screenshot of the screen is often the fastest
possible bug report — much of what goes wrong in a TV interface is visible and hard to describe.

## ⚠️ Redact before you paste

Logs and Home Assistant details routinely contain things you didn't mean to publish:

- **Local IP addresses** of your Home Assistant server or your box
- **Access tokens** and provider passwords — anything from Live TV setup, and any long-lived token
- **Entity ids and area names**, which describe the layout and contents of your home

This is a public repository. Anything you paste is public permanently and is indexed by search
engines. Replace real values with `192.168.x.x`, `<token>`, and so on. The issue form has a
checkbox for this; please actually do it rather than tick it.

## What happens to your issue

Development happens in a private repository. That has one consequence worth knowing about:

- **Your issue stays here, and stays yours.** It is never moved. The thread you filed is the one
  that gets answered, and the link you have keeps working.
- **You will not see the development work**, and you won't see cross-links to it. That is not
  silence — progress is reported as comments **on your issue**, because that's the only place you
  can see them.
- **Your issue is closed by hand, with an explanation** of what changed and in which version.
  If something closes without a reason that makes sense to you, say so and it will be reopened.

Fixes are announced in [CHANGELOG.md](CHANGELOG.md).

## Pull requests

This repository holds documentation, so corrections to it — a broken link, a wrong instruction, a
typo — are welcome as pull requests.

**Code changes cannot be accepted here**, because the app's source isn't in this repository. If
you have a change in mind, open a Discussion first; it's better to talk about it than to write
something that has nowhere to go.
