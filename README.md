# ManuNotes Releases

Built `.dmg` installers for [ManuNotes](https://github.com/ManuNotes/ManuNotes),
a macOS edge-docked notes widget. Source code lives in the private ManuNotes
repo; this repo only holds release artifacts.

## Download

Grab the latest `.dmg` from [Releases](../../releases), open it, and drag
ManuNotes.app to Applications.

### "Apple could not verify..." warning

ManuNotes isn't notarized by Apple yet (that requires a paid Apple Developer
account), so macOS Gatekeeper flags it as unverified the first time you open
a `.dmg` downloaded from a browser. To open it:

1. Go to **System Settings → Privacy & Security**.
2. Scroll to the security section — you'll see a message that ManuNotes.app
   was blocked, with an **"Open Anyway"** button next to it. This only
   appears after the first blocked attempt to open the app.
3. Click **Open Anyway**, then confirm in the dialog that follows.

On older macOS versions, right-clicking (or Control-clicking) ManuNotes.app
and choosing **Open** works instead.

## Versions

Releases here follow the same version numbers as the ManuNotes source repo
(see its `CHANGELOG.md` for what changed in each one).
