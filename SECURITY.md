# Security

UnitPad is a static, local-first app. Your sheets live in your browser, and
there is no account. The app sends nothing to us except the optional
exchange-rate request. That leaves a small surface. Report problems privately
all the same.

**Do not open a public issue for a security problem.**

Report it with GitHub's
[private vulnerability report](https://github.com/UnitPad/unitpad-feedback/security/advisories/new)
(Security tab → **Report a vulnerability**). It stays private until a fix is out.

In scope:

- The app served at <https://unitpad.app> and its same-origin `/api/fx` function.
- Anything that could expose a reader's sheets, or make the app run code it
  should not.

Out of scope: findings that require a compromised device, a malicious browser
extension, or physical access.

Include the build, the browser, and steps to reproduce. Select **Copy report
details** in the command palette to get the first two. Give us a reasonable window to
fix it before disclosing publicly. Never paste a real sheet's private contents
into a public issue.
