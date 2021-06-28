---
description: >-
  Athens Research publishes many types of documentation, from product usage
  how-to guides to details on company hiring processes. Here's how to contribute
  fixes and improvements across the board.
---

# Improve the handbook & documentation

Athens Research uses this handbook as the source of truth for all its documentation and information on using Athens, contributing to development, governance, and more.

The files in the  [`athensresearch/handbook` repository](https://github.com/athensresearch/handbook) are published to the [Athens Handbook](https://athensresearch.gitbook.io/handbook/) with GitBook.

### Contributing to the handbook

All contributors, and contributions of any type, are welcome. A community of many voices and perspectives produces the most inclusive and accurate documentation.

Learn about current priorities and TODOs by checking out the [Handbook project](https://github.com/athensresearch/handbook/projects/3) on GitHub, which is where the Athens community discusses and organizes, coordinates, and claims tasks related to the handbook.

If you want to make the handbook better, but don't want to work on the handbook itself, [filing issues](file-and-verify-issues.md) for missing our outdated information is incredibly helpful to the handbook team.

#### Handbook team

We currently have a small team of contributors who regularly work on the aforementioned TODOs in the Handbook project. If you're interested in joining, log onto our [Discord community](https://discord.gg/GCJaV3V) and check out the `#documentation` channel, then DM **Joel** to start the conversation.

### Language and tone

Our handbook should assume zero prior knowledge. Be descriptive without the unnecessary use of jargon. If jargon is unavoidable, link to our glossary or external educational pages that describe the jargon/concepts.

### Editing the handbook

There are two ways to make changes to the handbook:

1. [**GitHub**](contributing-documentation.md#contribute-with-github): Edit Markdown files in a new branch, then submit a pull request for review from members of the Athens core team or community.
2. [**GitBook**](contributing-documentation.md#contribute-with-gitbook): If you're less comfortable with using GitHub or editing Markdown, use rich-text, drag-and-drop editing tools to edit the handbook directly.

#### GitHub

Contributing to documentation with GitHub requires a few things:

* A GitHub account \(available for free\).
* A fundamental understanding of how Git works. Check out these resources to get started:
  * [Git-SCM](https://git-scm.com/book/en/v2), especially the [_Git Basics_](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository) chapter
  * [Set up Git](https://docs.github.com/en/github/getting-started-with-github/set-up-git)

First, [create a fork](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) of the [`athensresearch/handbook` repository](https://github.com/athensresearch/handbook).

![The fork button on the Athens handbook repository](https://user-images.githubusercontent.com/1153921/118381382-36474500-b59f-11eb-8ac4-e30369ba1920.png)

Clone the repository to your local machine with `git clone https://github.com/YOUR-GITHUB-USERNAME/handbook.git` \(or `git clone git@github.com:YOUR-GITHUB-USERNAME/handbook.git` if you use an SSH key to interact with GitHub\), then navigate to that directory and create a new branch: `git checkout -b BRANCH-NAME`.

Use your favorite text editor to make your changes. Add, commit, and push them to your branch on _your_ fork of the handbook repository with `git push origin BRANCH-NAME`.

Head over to the [pull requests](https://github.com/athensresearch/handbook/pulls) tab on the handbook repository. If you just recently pushed your changes, you should see a yellow box with the name of your fork+branch. Click **Compare & pull request** to create a pull request \(PR\).

![Creating a new PR with a recent push](https://user-images.githubusercontent.com/1153921/118381383-36dfdb80-b59f-11eb-93b5-f6efd6aa26d1.png)

Give your PR a descriptive title. In the textarea below, describe your changes and how they'll help other members of the Athens community. If you're making changes based directly on an existing GitHub issue or discussion, reference it here so reviewers can understand the full context.

Click **Create pull request** to create the PR. A member of the Athens team will be by shortly to review, provide feedback as required, and merge!

#### Images

The best way to attach images to your handbook contributions is to upload image assets to GitHub.

Drag-and-drop your image into the textarea at the bottom of any issue or PR.

1. ![Uploading a file to GitHub](https://user-images.githubusercontent.com/1153921/118381822-e6b74800-b5a3-11eb-9c0f-42850d33093f.gif)

GitHub returns an `<img>` element with the file uploaded to their content delivery network \(CDN\):

```text
<img width="1440" alt="Creating a new PR with a recent push" src="https://user-images.githubusercontent.com/1153921/118381383-36dfdb80-b59f-11eb-93b5-f6efd6aa26d1.png">
```

Add this string to your document to embed the image.

#### GitBook

Contributing to documentation with GitBook requires an invitation to the app.

To get started, join our [Discord community](https://discord.gg/GCJaV3V) and check out the `#documentation` channel. Say hello, let us know how you'd like to help, and DM **Joel** for an invitation to GitBook as a writer.

Once you've been given access to GitBook with writer permissions, there are a few ways to suggest or make changes:

To suggest changes, highlight a portion of text and click on the **+** bubble that appears to the right. Write in your comment and click **Comment in a new draft**. Other members can see and respond to your comment to discuss more or start improving.

To make changes directly:

* Open a file and make your changes using the built-in editor.
* Hover over the popup in the bottom-left corner. Add a description of your changes in the text area and click **Save**.
* At this point, other writers and administrators can see your edits. Send a message on the `#documentation` channel on [Discord](https://discord.com/invite/as9h8yHNfD) to encourage others to respond and provide feedback.
* Once you feel comfortable merging, click the **Merge** button. GitBook immediately publishes your changes and commits them back into the handbook repository.

### Handbook structure

* **Welcome**
  * Stored in the main `README.md`.
* **About us**
  * Information about Athens Research, what's new, and our vision.
  * Stored in `/about-us/`.
* **Athens User Guide**
  * Product documentation for the [Athens](https://github.com/athensresearch/athens) desktop or [web](https://github.com/athensresearch/athens-backend) \(self-hosted\) application.
  * Stored in `/community/athens-guide/`. 
* **Athens Community Guide**: 
  * Guides on the many ways of contributing to the Athens community and ecosystem.
  * Stored in `/community/get-involved/`.
* **Company**
  * Information for Athens Research as a company, including its core team, contributors, and operations.
  * Stored in `/company/`.
* **Help**
  * Contact information, answers to common questions, and a glossary of Athens-specific terminology and industry jargon.
  * Stored in `/help/`.

