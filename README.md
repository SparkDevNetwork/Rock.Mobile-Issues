# Rock.Mobile TV Issue Tracker

For a successful issue submission please read this entire readme. We care about the quality of Rock's Apple TV project, but with our limited resources we can only take complete and detailed issue submissions. Please understand that we are not trying to be difficult, but rather protecting our very limited resources.

Rock for Apple TV is a complex collection of 3rd party frameworks as well as some custom elements. As such, we can only support issues with the TV Shell directly. If your bug report is not actually the shell we will close the issue and direct you to the proper place.

We are also very limited on the resources we have to investigate bug reports. What this means is that you _must_ provide exact and detailed steps to reproduce your problem. If we look at the issue and there is not enough details for us to replicate the problem then we will close the issue.

Feature requests should be made at https://community.rockrms.com/Ideas with the Domain set to Apple TV.

Examples of things we are unable to help with:
* Issues that only manifest on your custom-built applications - you must be able to reproduce on the blue or orange app.
* Syntax errors with XAML
* Xamarin Forms XAML elements (StackLayout, Grid, etc.)
* Bugs in the iOS/Android (believe it or not this happens)
* "How do I..." questions
* Poorly written description of problem
* Inadequate reproduction steps
* Lack of XAML that reproduces the problem

Bugs must be reproducible with either the Blue or Orange app. If the only way to reproduce the bug is in your own custom built application then you must go through your app partner to report the bug.

If your bug is a simple visual bug that can be demonstrated with a screenshot then you must provide a screenshot showing the issue, even if it seems obvious. This must also be a full-device screenshot, this can not be cropped down. You must still provide the necessary XAML to reproduce the issue.

If your bug requires a series of steps (tap this, then tap this, then tap this) then you _must_ make a video that demonstrates the problem and the steps involved. There are on-device screen recorders you can use or you can also just use a camera (or another phone) to record.

If the bug you are reporting is XAML related you must include the **entire** XAML required to reproduce - this means we should be able to copy and paste your XAML into (for example) a Content block and see the problem. If you give us just a tiny snippet of the XAML then your issue will be closed.

You must also provide a minimal reproduction example (read https://stackoverflow.com/help/minimal-reproducible-example). If you paste 2 pages worth of XAML for a bug that has to do with a single node element, we will probably close your issue. For example, if you are reporting an issue when using a Label next to an Image with shadow, don't include buttons, grids or other elements that are not absolutely required to demonstrate the problem.
