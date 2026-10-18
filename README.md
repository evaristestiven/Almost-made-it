# Almost Made It! — FOREST-28

## Latest complete Godot/Xogot project

**[Download FOREST-28.zip](https://raw.githubusercontent.com/evaristestiven/Almost-made-it/main/downloads/Almost-Made-It-FOREST-28.zip)**

[Alternative GitHub file page](https://github.com/evaristestiven/Almost-made-it/blob/main/downloads/Almost-Made-It-FOREST-28.zip) — use Download raw file.

Download the named ZIP directly. GitHub's automatic Source code archive is a wrapper containing the download files, not the extracted game.

### Included gameplay upgrade

- Three raised stepping-stone links, two optional coin gardens and alternating courtyard approaches.
- Two rising gorge ferries, plus the existing moving platforms, bars, pendulums, recovery decks and checkpoints.
- Manual swipe-and-drag, jump, avatar, player-follow camera and solid/knockback physics preserved; Levels 2–10 unchanged.

### New verified nature assets

Pine_1 and Pine_5 now mix with the original detailed broadleaf trees in Level 1. Their original geometry buffers and texture references are intact. They reuse the existing bark/normal maps and the supplied Leaf_Pine_C atlas, imported at 1024px with mipmaps while preserving the original PNG.

Pine_2/3/4 pairs were checked but not imported in this controlled subset. TwistedTree_5 is excluded because its geometry buffer and referenced bark/leaf textures are incomplete; the report names the missing files.

### Open in Xogot

1. Download FOREST-28.zip in Safari and unzip it in Files into a new folder.
2. Open `AlmostMadeIt-FOREST-28/project.godot` in Xogot; let imports regenerate.
3. Confirm title **Almost Made It! FOREST-28**, then launch Level 1 First Steps.
4. Test the optional gardens, precision jumps, rising ferries, knockback and checkpoint recovery.
5. To inspect both pine models separately, open `scenes/visual_tests/pines_test.tscn` and run that scene.

Keep your previous project as a backup. A new project title/folder may use separate local save storage.

### Actual validation

FOREST-28: 6 source runtime runs / 569 assertions; 4 fresh-package suites / 449 assertions; 122 script parse checks; four rendered views inspected. All passed. Full 60Hz route: 165.08 simulated seconds, zero falls, five coins, one victory. ADVENTURE-27's retained gameplay also passed full-route checks at 30/60/120Hz.

These are scripted simulation times, not human first-clear or on-device FPS measurements. iPhone/iPad performance and real touch feel remain unverified. This is a targeted upgrade toward the forest reference; terrain faceting, cloud banding and limited plant variety remain.

[FOREST-28 report](downloads/FOREST28_REPORT.txt) · [Checksum](downloads/Almost-Made-It-FOREST-28.sha256)

### Earlier builds

[ADVENTURE-27](downloads/Almost-Made-It-ADVENTURE-27.zip) · [WORLD-25](downloads/Almost-Made-It-WORLD-25.zip) · [WORLD-25 acceptance evidence](qa/level1-acceptance/QA_REPORT.txt)
