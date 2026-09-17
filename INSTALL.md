# Installing CrewDB

CrewDB is a small app for running a student film set as the 1st AD: crew,
schedules, call sheets, locations, budgets and gear, all in one place. Tommy
Van Dyke built it for his own productions and shares it with the program.
Everything you enter stays on your Mac.

## What you need

- **A Mac with Apple silicon** (M1 or newer). To check, open the Apple menu
  and choose **About This Mac**. It should say **Chip: Apple M…**. Macs with
  an Intel processor can't run this version.
- **macOS 13 Ventura or newer** (same window, next to "macOS").

## Install

1. Download CrewDB:
   **https://github.com/tommyvd02-ui/crewdb-releases/releases/latest/download/CrewDB_AppleSilicon.dmg**
2. Open **CrewDB_AppleSilicon.dmg** from your Downloads folder. A window opens
   with CrewDB and a shortcut to your Applications folder.
3. **Drag CrewDB onto Applications.**
4. Close the window and eject the disk image (click ⏏ next to "CrewDB" in the
   Finder sidebar). You can delete the .dmg file now.
5. Open CrewDB from your Applications folder, or press ⌘-Space and type
   "CrewDB".

> **Run CrewDB from Applications.** Don't open it straight from the disk image
> or your Downloads folder. CrewDB can't install its own updates from either
> place.

## The first time you open it

macOS asks: *"CrewDB" is an app downloaded from the Internet. Are you sure you
want to open it?* Click **Open**. CrewDB is signed and checked by Apple, so
you'll only see this once.

If macOS says CrewDB **can't be opened at all**, your Mac is probably an Intel
Mac or is running a macOS version older than 13.

## Saving exports

The first time you export something (a call sheet PDF, a spreadsheet), macOS
asks whether CrewDB may use your **Downloads** folder. Click **Allow**. Exports
are saved there.

If you clicked "Don't Allow" by mistake, open System Settings › Privacy &
Security › Files and Folders, find CrewDB, and turn on **Downloads**.

## Updates

CrewDB checks for new versions by itself. When one is ready, you'll see
**Restart to update**. Click it and CrewDB reopens on the new version with
your data untouched. You never need to download the disk image again.

Your version number is at the bottom of **Settings**.

## Where your data lives

Everything is stored on your Mac, in:

```
~/Library/Application Support/com.tommyvandyke.crewdb.public
```

To open that folder, go to Finder › Go › Go to Folder…, then paste the path.

- CrewDB keeps backup snapshots while you work, when you quit, and before any
  restore. To go back to an earlier state, open **Settings › Backups** and
  click **Restore** next to the snapshot you want.
- Deleting the app doesn't delete your data. If you install CrewDB again,
  everything is still there.
- **Moving to a new Mac:** quit CrewDB, then copy that whole folder to the
  same place on the new Mac before you open CrewDB there.

## Optional: Google Maps and Google Drive

CrewDB works fully without Google. Two extras live under **Settings ›
Advanced**, and both use your own Google Cloud account:

- **Google Maps:** add your own Maps API key to get address and business
  search, plus a **Map** tab in each project's Production section.
- **Google Drive:** connect your own Google OAuth client, and CrewDB can create
  a folder for each project and upload call sheets to it. This one is for
  people comfortable with the Google Cloud console.

## Reporting a bug

Send Tommy a message and include:

1. **Your CrewDB version** (bottom of Settings) and your macOS version (Apple
   menu › About This Mac).
2. **What you did, step by step,** what you expected to happen, and what
   happened instead.
3. **A screenshot.** Press ⌘-Shift-4 and drag over the problem, or press
   ⌘-Shift-5 to record the screen.

Please don't send your data folder unless he asks for it. It holds your
crew's phone numbers and emails.

## Uninstalling

Drag CrewDB from Applications to the Trash. Your data folder (above) stays
behind. Delete it too if you want to remove everything.
