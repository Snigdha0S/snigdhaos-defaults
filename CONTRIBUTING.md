# Contributing to Snigdha OS

[Snigdha OS](https://snigdhaos.org) is our way to hopefully help make open source documentation easier. If you're interested in contributing to **Snigdha OS**, hopefully, this document makes the process for contributing clear.

The [Open Source Guides](https://opensource.guide/) website has a collection of resources for individuals, communities, and companies who want to learn how to run and contribute to an open source project. Contributors and people new to open source alike will find the following guides especially useful:

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Building Welcoming Communities](https://opensource.guide/building-community/)

## Code of Conduct

**Snigdha OS** has adopted a Code of Conduct that we expect project participants to adhere to. Please read [the full arcticle](https://code.fb.com/codeofconduct) so that you can understand what actions will and will not be tolerated.

## Get Involved

There are many ways to contribute to **Snigdha OS**, and many of them do not involve writing any code. Here's a few ideas to get started:

- Simply start using Snigdha OS. Go through the [Getting Started](https://snigdhaos.org/get-started) guide. Does everything work as expected? If not, we're always looking for improvements. Let us know by [opening an issue](#issues).
- Look through the [open issues](https://github.com/Snigdha0S/). Provide workarounds, ask for clarification, or suggest labels. Help [triage issues](#triaging-issues-and-pull-requests).
- If you find an issue you would like to fix, [open a pull request](#pull-requests). 
- Read through the [Snigdha OS docs](https://snigdhaos.org/docs/installation). If you find anything that is confusing or can be improved, you can click "Edit this page" at the bottom of most docs, which takes you to the GitHub interface to make and propose changes.
- Take a look at the [features requested](https://github.com/Snigdha0S/snigdhaos-arctic/labels/feature) by others in the community and consider opening a pull request if you see something you want to work on.

Contributions are very welcome. If you think you need help planning your contribution, please ping us on Twitter at [@SnigdhaOS](https://twitter.com/SnigdhaOS) and let us know you are looking for a bit of help.

### Triaging Issues and Pull Requests

One great way you can contribute to the project without writing any code is to help triage issues and pull requests as they come in.

- Ask for more information if you believe the issue does not provide all the details required to solve it.
- Suggest [labels](https://github.com/Snigdha0S/snigdhaos-arctic/labels) that can help categorize issues.
- Flag issues that are stale or that should be closed.
- Ask for test plans and review code.

## Our Development Process

**Snigdha OS** uses [GitHub](https://github.com/Snigdha0S/snigdhaos-arctic) as its source of truth. The core team will be working directly there. All changes will be public from the beginning.

All pull requests will be checked by the continuous integration system, GitHub actions. There are unit tests, end-to-end tests, performance tests, style tests, and much more.

### Branch Organization

Docusaurus has one primary branch `master` and we use feature branches with deploy previews to deliver new features with pull requests.

## Issues

When [opening a new issue](https://github.com/Snigdha0S/snigdhaos-arctic/issues/new/choose), always make sure to fill out the issue template. **This step is very important!** Not doing so may result in your issue not being managed in a timely fashion. Don't take this personally if this happens, and feel free to open a new issue once you've gathered all the information required by the template.

> **Please don't use the GitHub issue tracker for questions.** 
> If you have questions about using Docusaurus, use any of our [support channels](https://forum.snigdhaos.org/t/support), and we will do our best to answer your questions.

### Bugs

We use [GitHub Issues](https://github.com/Snigdha0S/snigdhaos-arctic/issues) for our public bugs. If you would like to report a problem, take a look around and see if someone already opened an issue about it. If you are certain this is a new, unreported bug, you can submit a [bug report](#).

- **One issue, one bug:** Please report a single bug per issue.
- **Provide reproduction steps:** List all the steps necessary to reproduce the issue. The person reading your bug report should be able to follow these steps to reproduce your issue with minimal effort.

If you're only fixing a bug, it's fine to submit a pull request right away but we still recommend filing an issue detailing what you're fixing. This is helpful in case we don't accept that specific fix but want to keep track of the issue.

### Feature requests

If you would like to request a new feature or enhancement but are not yet thinking about opening a pull request, you can file an issue with the [feature template](https://github.com/facebook/docusaurus/issues/new?assignees=&labels=feature%2Cstatus%3A+needs+triage&template=feature.yml) in the form of an **elaborated RFC**. Alternatively, you can use the [Canny board](https://docusaurus.io/feature-requests) for more casual feature requests and gain enough traction before proposing an RFC.

### Proposals

If you intend to make any non-trivial changes to existing implementations, we recommend filing an issue with the [proposal template](https://github.com/facebook/docusaurus/issues/new?assignees=&labels=proposal%2Cstatus%3A+needs+triage&template=proposal.yml). This lets us reach an agreement on your proposal before you put significant effort into it. These types of issues should be rare.
