# UnitPad feedback

[UnitPad](https://unitpad.app) is a local-first, unit-aware notepad for
calculations, powered by [Numbat](https://numbat.dev). Your sheets stay on your
device. There is no account.

**This repository is the feedback channel.** It is where problem reports, questions,
and ideas go.

| What you have | Where it goes |
| --- | --- |
| Something is broken | [Problem report](https://github.com/UnitPad/unitpad-feedback/issues/new?template=bug.yml) |
| Sheets missing, or an upgrade damaged your data | [Data problem](https://github.com/UnitPad/unitpad-feedback/issues/new?template=data.yml) |
| A value, function or unit in a module is wrong or out of date | [Correction](https://github.com/UnitPad/modules/issues/new?template=correction.yml), in the modules repository |
| An idea for something UnitPad should do | [Feature request](https://github.com/UnitPad/unitpad-feedback/issues/new?template=feature.yml) |
| A question, or something to show | [Question](https://github.com/UnitPad/unitpad-feedback/discussions/new?category=q-a) |
| A suspected security problem | [Security problem](https://github.com/UnitPad/unitpad-feedback/security/advisories/new). See [SECURITY.md](SECURITY.md) |

## Send it from the app

Select **Open feedback** in the command palette, then the kind. The form opens with the build, browser and device filled in, and an **Environment**. With it, we can reproduce your report with the same engine and window size.

No GitHub account? Select **Copy report details** in the command palette, and email what it copies. The address is in **Show open source licenses**.

## What makes a report easy to act on

- **Exact steps, and what you expected.**
- **A sheet that reproduces it.** Use **Download sheet**, and paste the text. For a long sheet, attach the file to a comment after you post. Remove anything private first.
- **The build and the browser.** If you did not use the app: select **Show open source licenses**, which says when the app was last built. Safari and iOS behave differently from Chrome, so say which you use.

Everything you post here is public. UnitPad keeps your sheets on your device.
This repository is the only place we ask you to share them, and only if you
choose to. Do not paste anything you would not want indexed.
