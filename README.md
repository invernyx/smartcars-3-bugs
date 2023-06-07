# smartCARS 3 Bug Reports
This is the official bug report repository for smartCARS 3. You may report bugs relating to core app functionality, plugin functionality, development experience and make suggestions for new features.

**Please do not report bugs relating to smartCARS 2**

## Reporting Bugs
Before reporting a bug, you must verify that the bug is not caused by a plugin. To do this, please disable all unverified plugins (any plugin in the app that does not have the "Verified" pill), and try to reproduce the bug.

If the bug is not caused by an unverified plugin, you should verify that your issue [has not already been reported](https://github.com/invernyx/smartcars-3-bugs/issues?q=is%3Aissue+is%3Aopen+label%3Abug%2C%22verification+required%22). If it has, please add a comment to the existing issue instead of creating a new one with any further information you may be able to present.

To report a bug, please create a [new issue](https://github.com/invernyx/smartcars-3-bugs/issues/new?assignees=&labels=verification+required&projects=&template=bug_report.yml&title=%5BBUG%5D+-+) using the bug report template.

## Suggesting Features
Before suggesting a feature, please verify that the feature [has not already been suggested](https://github.com/invernyx/smartcars-3-bugs/issues?q=is%3Aissue+label%3Asuggestion). If it has, please comment to the existing issue instead of creating a new one.

To suggest a new feature, please create a [new issue](https://github.com/invernyx/smartcars-3-bugs/issues/new?assignees=&labels=suggestion&projects=&template=feature_request.yml&title=%5BFEATURE%5D+-+) using the feature request template.

# Security Vulnerabilities
If you discover a security vulnerability within smartCARS 3, please create a new [Security Advisory](https://github.com/invernyx/smartcars-3-public-api/security/advisories/new). We require lots of technical information about the vulnerability, so please do not create a public issue.

### Bug Hunter Rewards Program
We have a Bug Hunter Rewards Program. You may be eligible for a reward if you discover a security vulnerability. The table of rewards is as follows:

| **Vulnerability**                                                                                                                     | **Reward** |
|---------------------------------------------------------------------------------------------------------------------------------------|------------|
| Permission elevation<br><br>Examples:<br> - Obtaining administrative rights<br> - Executing tasks which usually require administrator | $25        |
| Security Circumvention<br><br>Example:<br> - Bypassing obvious security controls, such as:<br>--Filesize limits<br>--Authentication   | $25        |
| Leaking sensitive or private information<br><br>Example:<br> - Obtaining credentials that were not intended for use                   | $25        |
*The examples provided are not exhaustive*

A valid vulnerability must:
- Occur in the latest version of smartCARS 3.
- Not cause a hang or crash.
- The user must not be aware at the time of the vulnerability - UAC prompts, visual warnings and other similar methods are not vulnerabilities.
- Not be a duplicate of an existing vulnerability - if you find a vulnerability that has already been reported, you will not be eligible for a reward.
- Not be a vulnerability in a third-party library - you should report this to the developers of that library.
- Not be intentional by design.

If your vulnerability does not meet these requirements, you are experiencing a bug, not a vulnerability. You can report your bug [here](https://github.com/invernyx/smartcars-3-bugs/issues/new?assignees=&labels=&template=bug_report.md&title=%5BBUG%5D+-+).

**We will respond to all security vulnerabilities as soon as possible.** Please do not disclose the vulnerability to the public until we have had a chance to respond.
