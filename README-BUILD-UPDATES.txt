HAUNTED HEISTS WEBSITE — BUILD / PATCH NOTES
==============================================

FILES TO UPDATE
---------------
1. haunted-heists.html
   Replace the current Haunted Heists page with this file.

2. hh-builds.css
   Add this file beside style.css (or replace your earlier hh-builds.css draft).

CURRENT RELEASE HISTORY
-----------------------
v0.0.1 — Singleplayer MVP — Aug 14, 2026
v0.1.0 — EOS WAN Multiplayer — Aug 16, 2026
v0.2.0 — Multiplayer Lobby + Villa WIP — Aug 21, 2026

VERSION RULES GOING FORWARD
---------------------------
Patch / hotfix:
    v0.2.0 -> v0.2.1

Meaningful feature or content milestone:
    v0.2.x -> v0.3.0

Full commercial release:
    v1.0.0

Alpha / Beta / Early Access labels are separate from the numeric version.
Do not force a specific development stage onto a number in advance.

PAGE LAYOUT
-----------
Bottom of Haunted Heists page:

1. Latest Build / Download
2. Current Patch Notes (always expanded)
3. Previous Patch History
   - Collapsed by default
   - Click to expand
   - History container becomes scrollable as it grows
4. Credits
5. Footer

CURRENT DOWNLOAD
----------------
v0.2.0 currently links to:
HauntedHeists_MultiplayerLobbyBuild_Windows.zip

The website uses the Google Drive file-view link so visitors can download the
archive without exposing or embedding the 1.5 GB file in the GitHub Pages repo.

ADDING THE NEXT PATCH
---------------------
Example: v0.2.1

1. Update the version/date/title in the Latest Build card.
2. Change its Google Drive link to the new ZIP.
3. Replace the expanded current patch notes.
4. Move the old v0.2.0 notes into a <details class="patch-history-item"> block.
5. Keep newest historical patch at the top.
