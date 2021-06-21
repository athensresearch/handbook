---
description: >-
  Want to dive into the Athens Research community? This overview will give you
  more than a dozen ways to make place better—most of which don't even involve
  writing code.
---

# Overview

The final Athens vision is for everyone, one day, to learn how to learn anything.

To do that, it is mission-critical to create a space and culture where we can [work with one another and learn from one another](https://github.com/athensresearch/athens/blob/master/CODE_OF_CONDUCT.md).

We're always looking to bring new people and new ideas into Athens. There's plenty of ways to get involved, from development, design, documentation, and more. Don't hesitate to jump in!

### Get started with the Athens Research community

* Review the [Code of Conduct](code-of-conduct.md).
* Complete the Contributors License Agreement.
* Check out ways to [get involved](learning-at-athens-academy-education/).
* Join our mailing list by [visiting our blog](https://athens-research.ghost.io/) and clicking **Subscribe**.
* Participate in conversations on our [Discord server](https://discord.gg/as9h8yHNfD).
* [Follow updates](../../about-us/whats-new-in-athens.md) on new Athens versions.

### Go deeper

* [Connect with Athens](learning-at-athens-academy-education/connect-on-social-media.md) on social media.
* Ask and answer questions 
* [Share your workflows](learning-at-athens-academy-education/share-your-experiences.md) to help others become Athens gurus.
* [Report bugs](learning-at-athens-academy-education/file-and-verify-issues.md) when something is broken.
* [Request new features](learning-at-athens-academy-education/request-new-features.md) to add functionality.
* [Improve this handbook](learning-at-athens-academy-education/contributing-documentation.md) to make Athens more transparent and approachable.
* [Improve the design](learning-at-athens-academy-education/contributing-design.md) of the Athens app or website.
* Submit a [sample template or database](learning-at-athens-academy-education/submit-templates-or-databases.md) so that others can learn from the workflows you've built.

### Working with the Athens codebase

* Set up your deployment environment
* Check out editors and other tools that will support your contributions
* Follow the roadmap, releases, and current projects
* Learn about the Athen's testing process

### Developers

* Join our [Discord](https://discord.gg/GCJaV3V) and check out the `#🤖-programming` channel. The channel is for anything engineering-related!
  * Post work updates in the `#🛠-build-in-public`. This keeps the team on the same page! Let's avoid stepping on each others toes, minimize blockers / dependencies, and cheer each other on!
  * Ask for someone to review your work or PR in the `#🔩-review-requests` channel.
* Watch the repo and bookmark our [Project Board](https://github.com/athensresearch/athens/projects/2). This is the ultimate source of truth for product roadmapping.
* Learn how to [run Athens locally](../../company/athens-research-governance-and-operations/engineering/development.md#running-athens-locally) to create a development environment.
* To start working on your PR, you have a few ways to get started:
  1. Ask a question in our `#🤖-programming` [Discord](https://discord.gg/GCJaV3V) channel
  2. Comment on one of the existing top-level issues on the project board
  3. Create a PR draft or issue, then assign yourself \(prefer drafts over new issues\)
* In all the cases above, try to scope out what you want to do and how, to the extent that you can at the start of a task! If you aren't sure about the scopes, chat in our Discord. If you feel confident, go ahead and start your PR draft — you don't need permission to start!
* Read [Product Development at Athens](https://www.notion.so/athensresearch/Product-Development-at-Athens-4c99e37d1713441c99360668c39e5db7) to see our shipping philosophy. It's more nuanced than just "agile", with some inspiration from Basecamp.
* If you don't have experience programming with Clojure, checkout our learning resources and join [ClojureFam](https://github.com/athensresearch/ClojureFam) to learn with some friends! In our experience, it takes ~4 weeks of part-time study to begin making solid code contributions to Athens.

### Designers

* Join our [Discord](https://discord.gg/GCJaV3V) and see what's happening in the `#🖋-design` channel.
* Duplicate the [Athens Design System](https://www.figma.com/file/XITWUHZHNJsIbcCsBkOHpZ/Athens-Design-System?node-id=0%3A1) on Figma to get the building blocks for creating UIs and workflows.
* See previous concepts in the [Product Design Sandbox](https://www.figma.com/file/iCXP6z7H5IAQ6xyFr5AbZ7/Product-Design-Sandbox?node-id=183%3A37). This Figma is no longer actively used, but seeing previous work can help!

### Others

* Have other superpowers?! Join our [Discord](https://discord.gg/GCJaV3V), introduce yourself in `#🐣-introductions`, and ask around in `#⛲️-general`!

### Git and GitHub Style Guide

#### Commits

Follow guidelines from [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/). Specifically, begin each commit with one of the following types:

```text
build:
ci:
chore:
docs:
feat:
fix:
perf:
refactor:
revert:
style:
test:
```

See some real examples in our [commit history](https://github.com/athensresearch/athens/commits/master).

#### Issues

Please create issues using [our templates](https://github.com/athensresearch/athens/issues/new/choose). However, you will almost certainly get feedback and help faster in our [Discord](https://discord.gg/GCJaV3V)!

#### Pull Requests

If your PR is related to other issue\(s\), reference it by issue number. You can close issues smoothly with [GitHub keywords](https://help.github.com/en/enterprise/2.16/user/github/managing-your-work-on-github/closing-issues-using-keywords):

```text
close #1
fix #2
resolve #2
```

This repo only allows those with merge permissions to "Squash and Merge" PRs. This makes reverts easier if they are needed.

