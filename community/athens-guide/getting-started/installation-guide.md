# Installation Guide

* [Install Athens](#install-athens)
  * [Windows](#windows)
  * [OS X](#os-x)
  * [Linux](#linux)
* [Post-installation](#post-installation)
  * [Finding where your data is stored](#finding-where-your-data-is-stored)
  * [Importing an existing database](#importing-an-existing-database)
  * [Creating a new database](#creating-a-new-database)
  * [Syncing your data between machines](#syncing-your-data-between-machines)
  * [Updating Athens](#updating-athens)

## Install Athens

Open the [Releases page](https://github.com/athensresearch/athens/releases).

Click on the **Assets** tab for the latest release.

![Screenshot of the Releases page with an arrow pointing to the Assets tab](https://user-images.githubusercontent.com/15487/122689808-0bc65880-d1eb-11eb-96eb-43ac464de143.png)

![Screenshot of the Releases page with the Assets tab expanded with its contents marked with a red square](https://user-images.githubusercontent.com/15487/122689924-a888f600-d1eb-11eb-9d4b-df8690f43fb4.png)

Find the next section of this page appropriate for your operating system.

### Windows

1. Download `Athens-Setup-1.0.0-[VERSION].exe`.
2. Double-click it to run it.
3. The installer will run and then launch Athens, at which point it should be available in your Start menu.
4. At this point, you can delete the file you downloaded in step 1.

### OS X

If your OS X computer contains an [M1 chip](https://en.wikipedia.org/wiki/Apple_M1) (i.e. was purchased during or after November 10, 2020), you can download either `Athens-1.0.0-[VERSION]-arm64-mac.zip` or `Athens-1.0.0-[VERSION]-arm64.dmg`.

If your OS X computer contains an [Intel chip](https://en.wikipedia.org/wiki/Mac_transition_to_Intel_processors) (i.e. was purchased between January 2006 and early November 2020), you can download either `Athens-1.0.0-[VERSION]-mac.zip` or `Athens-1.0.0-[VERSION].dmg`.

If you download a `.zip` file:

1. Double-click it to have Archive Utility automatically extract it into the same folder.
2. Move the extracted `Athens` application into your `Applications` folder.

If you download a `.dmg` file:

1. Double-click it to mount it.
2. Find the mounted image on your desktop and double-click it to open it.
3. Drag the contained `Athens` application into your `Applications` folder.
4. Right-click the mount on your desktop and select the `Eject` option.

At this point, you can delete whichever file you downloaded.

### Linux

The Linux release is a standalone [AppImage](https://appimage.org/) executable.

1. Download `Athens-1.0.0-[VERSION].AppImage`.
2. Change permissions of the file to make it executable, e.g. run the following command in a terminal from the directory containing the file.

   ```sh
   chmod a+x Athens-1.0.0-[VERSION].AppImage
   ```

3. Execute the file.

## Post-installation

### Finding where Athens stores your data

By default, Athens opens an initial knowledge graph that's stored in a local file called `index.transit`, which is a [datascript](https://github.com/tonsky/datascript) database at rest. The `index.transit` file and every other file in the folder, minus the backup (`.bkp`) files, make up the Athens database.

To find the location of this file for your operating system, click the **Choose Database** icon in the top-right corner of the Athens window.

![Athens window with a red arrow pointing to the Choose Database icon](https://user-images.githubusercontent.com/15487/122690410-108d0b80-d1ef-11eb-8c4c-cd502b28e318.png)

The file location appears in the **Open** tab that's displayed by default.

![Choose Database modal with the current database file location marked with a red square](https://user-images.githubusercontent.com/15487/122767507-5cc86200-d268-11eb-93cb-858cc198320e.png)

### Importing an existing database

If you've used [Roam](https://roamresearch.com/) and want to bring your content into Athens, see documentation on [Athens import features](../feature-list/import.md).

### Creating a new database

To create a new database in a different location, click the **New** tab, enter a database name, and click the **Browse** button to select a directory to house the database files.

![Choose Database modal with the New tab and its Database Name text box and Browse button marked by red arrows](https://user-images.githubusercontent.com/15487/122768180-f7c13c00-d268-11eb-959c-22bb2170c585.png)

### Syncing your data between machines

If you need to edit your knowledge graph from multiple machines or on different networks, you have two choices:

1. Use a file synchronization tool like [Dropbox](https://www.dropbox.com) or [OneDrive](https://www.microsoft.com/en-us/microsoft-365/onedrive/online-cloud-storage). While Athens warns you about updated blocks coming from these tools, you should take care not to edit the same database from multiple machines at the same time.
2. Run the [Athens backend](https://github.com/athensresearch/athens-backend) on a system like a [virtual private server](https://en.wikipedia.org/wiki/Virtual_private_server) (VPS) or [Heroku deployment](https://github.com/athensresearch/athens-backend#heroku) that you can access from every machine or network. This backend is in the process of being refactored into the [main Athens git repository](https://github.com/athensresearch/athens) (see [this issue](https://github.com/athensresearch/athens/pull/1170/) for details), but until that effort is completed, the existing archived backend can be used.

### Updating Athens

Athens will automatically download new releases and use them when restarted. As such, it's a good idea to restart Athens periodically.

Note that there may be issues with this automatic update feature in Windows; see [this issue](https://github.com/athensresearch/athens/issues/1248) for details.
