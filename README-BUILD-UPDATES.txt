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


INTERACTIVE ROADMAP
-------------------
The roadmap lives immediately above the Latest Build / Download section.

Milestones:
v0.0.1  First Playable
v0.1.0  First Multiplayer Build
v0.2.0  Improved Multiplayer (current)
v0.2.5  UI Polish
v0.3.0  Modern Villa
v0.4.0  Item Overhaul
v0.4.5  Equipment Planning
v0.5.0  Heist Tools
v0.5.5  Equipment Economy
v0.6.0  Objective Requirements
v0.7.0  Behavioral Ghost Types
v0.8.0  Outsiders
v0.9.0  Early Access Candidate
v1.0.0  Full Release

Roadmap behavior:
- Completed milestones use spectral green.
- Current milestone uses a larger gold dot.
- Planned milestones use dim outlined dots.
- Labels alternate above and below the line.
- Clicking a milestone updates the detail panel underneath.
- On narrow screens the timeline scrolls horizontally.

To update a milestone, search haunted-heists.html for its roadmap-node and edit:
data-title, data-status, data-description, data-highlights, and the visible roadmap-label.

Roadmap finish line:
- v0.9.0 is the Early Access readiness/stabilization milestone.
- v1.0.0 is the Full Release milestone.
- v1.0.0 gets a special terminal-node treatment so the end of the roadmap reads as a destination.
