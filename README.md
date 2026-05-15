# Rock Mobile Issue Tracker

**Read this in full before submitting.** We take Rock Mobile quality seriously. To protect
our limited resources, we only act on complete, detailed reports. Incomplete submissions
will be closed without investigation.

## Scope

This tracker covers issues with the Rock Core mobile app experience. If your report falls
outside that scope, we'll close it and point you in the right direction.

Feature requests belong at [community.rockrms.com/Ideas](https://community.rockrms.com/Ideas)
with the Domain set to Mobile.

## What We Can't Help With

We'll close issues that involve:

- Bugs that only appear in your custom-built app (see reproduction requirements below)
- Syntax errors in XAML
- Standard .NET MAUI elements (StackLayout, Grid, etc.)
- Bugs in iOS or Android itself
- "How do I..." questions
- Vague or incomplete problem descriptions
- Missing reproduction steps
- XAML-related bugs submitted without reproduction XAML

For general help, questions, and troubleshooting, join the [#mobile channel on Rock Community
Chat](https://community.rockrms.com/chat).

## Reproduction Requirements

All bugs must reproduce in the **Rock Core (orange) app**.

- [Download on the App Store](https://apps.apple.com/us/app/rock-core/id1498547817)
- [Get it on Google Play](https://play.google.com/store/apps/details?id=org.sparkdevnetwork.rockmobile&hl=en-US)

If a bug only reproduces in your custom-built app, report it through your app partner.

**Screenshots:** For visual bugs, include a full-device screenshot. Cropped screenshots
are not accepted. You must still include the XAML needed to reproduce the issue.

**Videos:** If reproducing the bug requires a series of steps, record a video showing the
full sequence. Use your device's built-in screen recorder, or record with another device.

**XAML:** For XAML-related bugs, include the **complete** XAML required to reproduce the
problem. We need to be able to paste it directly into a Content block and see the issue.
Partial snippets will result in a closed issue.

**Minimal reproduction:** Keep your XAML as small as possible. Read
[this guide](https://stackoverflow.com/help/minimal-reproducible-example) for what that
means. Two pages of XAML for a single-element bug will likely result in a closed issue.
For example, if the problem is a Label next to a shadowed Image, leave out buttons, grids,
and anything else not required to show the problem.
