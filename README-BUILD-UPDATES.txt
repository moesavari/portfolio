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
v0.2.0 — Improved Multiplayer + Villa WIP — Aug 21, 2026
v0.2.5 — UI Polish + Multiplayer Verification — Aug 23, 2026

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
Canonical public roadmap:

v0.2.5  UI & Interaction Polish (current)
        Host/Join redesign, visual consistency, map-selection sync, hover language,
        extraction/back-door interaction fixes

v0.3.0  Villa Update
        Fully integrate the Villa and begin map-level gameplay polish such as hiding spots

v0.3.5  Player State Polish
        Death spectator mode, optional death animation, panic threshold audio/visual feedback

v0.4.0  Item Revamp
        Procedural loot, item categories, inventory/equipment architecture

v0.4.5  Equipment Preparation UI
        Empty shared equipment pool; players add owned items; internal ownership backlog

v0.5.0  Heist Tools
        First tiered player items, consumables, traps and usable equipment

v0.5.5  Equipment Economy
        Purchasing, ownership, tier unlocks, use/loss/death reconciliation

v0.6.0  Secured Objectives
        Main objective gated behind puzzles, requirements or tools

v0.7.0  Ghost Types
        Distinct ghost behavior archetypes

v0.8.0  Outsiders
        Rival thieves, police and other external events

v0.9.0  Replayability & Maps
        Additional maps, procedural variety and broader job progression

v0.9.x  Tutorial Conversion
        Convert the original MVP house into a dedicated tutorial

v0.9.5  Character / Ghost Visual Overhaul
        New models, animation polish and art upgrades when resources permit

v1.0.0  Early Access
        Stabilization, balance, optimization and complete initial loop

The website roadmap starts at the current public milestone (v0.2.5).
Earlier versions remain in Patch History rather than occupying roadmap space.

Behavior:
- v0.2.5 is Current.
- Future milestones are Planned.
- Labels alternate above/below the line.
- Clicking a milestone updates the full public description panel.
- Timeline scrolls horizontally on smaller screens.
- v1.0.0 uses the finish-line styling and represents Early Access.

ROADMAP / VIDEO PRESENTATION
----------------------------
- Roadmap labels alternate strictly top / bottom across the full v0.0.1 -> v1.0.0 timeline.
- Gameplay showcase text identifies the footage as captured with v0.1.0.

v0.3.0 WEBSITE UPDATE — 2026-08-29
----------------------------------
Current roadmap milestone: v0.3.0 — Rich Neighbourhood
Current public patch: v0.3.0 — Rich Neighbourhood

Major public notes:
- New Rich Neighbourhood contract map
- Steam WAN sessions
- Redesigned Play/session/lobby flow
- Improved ghost cross-floor and balcony navigation
- Modular House Manager/editor tools
- Whole-house power + replicated randomized breaker selection
- Interaction/inventory/extraction/item-drop reliability improvements
- Official Paranormal Estates font
- Stability, performance, loading, and synchronization fixes

The v0.3.0 build download is intentionally set to UPLOAD PENDING until the new packaged ZIP has a public URL.


DUAL BUILD DOWNLOADS — v0.3.0+
-------------------------------
The current build card has two independent slots: Steam and Epic.

Both are currently set to Upload Pending.

To enable either slot:
- Replace href="#" with that build's public URL.
- Remove build-download-disabled and aria-disabled="true".
- Change build-platform-status from pending to available.
- Change "Upload Pending" to "Available".

The two builds do not need to go live at the same time.


v0.3.0 PUBLIC BUILD LINKS — 2026-08-29
--------------------------------------
Steam:
https://drive.google.com/file/d/1L4FiGm11T9js0My8L3goIarjRFN13p6o/view?usp=drive_link

Epic / EOS:
https://drive.google.com/file/d/16IieLuY91-qoZ9XurMQbcANrU6CF_KxG/view?usp=drive_link

Both v0.3.0 download slots are enabled and marked Available.

Hero title presentation:
PARANORMAL ESTATES:
HAUNTED ROBBERIES

Build monogram:
HR
