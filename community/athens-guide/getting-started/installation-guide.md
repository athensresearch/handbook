# Installation Guide

* Download Athens
* Import a Preexisting Database

## Download Athens

[**Download the free desktop app**](https://github.com/athensresearch/athens/releases), which creates a locally-stored knowledge graph. Click on the **Assets** tab for the latest release to find downloads that run Athens on macOS, Windows, and Linux.

If you're coming to Athens from Roam Research, check out the [import](../feature-list/import.md) doc for details on how to bring your Roam content over to Athens.

#### Hosting Your Own Data

When using the desktop app, Athens stores your knowledge graph in a local folder in a file called `index.transit`. This file never leaves your system.

If you need to edit your knowledge graph from multiple machines or on different networks, you have two choices:

* Use a file system tool like Dropbox or OneDrive. While Athens warns you about updated blocks coming from these syncing tools, you should take care not to edit the same database from multiple machines at the same time.
* Run the [Athens backend](https://github.com/athensresearch/athens-backend) on a system, like a virtual private server \(VPS\) or [Heroku deployment](https://github.com/athensresearch/athens-backend#heroku) that you can access from every machine or network.

## Import a Preexisting Database

