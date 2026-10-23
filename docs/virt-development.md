# VIRT development — From architecture to operational maps

Updated October 23, 2026 · Jason Von Holmes / Songtan Labs

**[Enter VIRT](https://holmesnet-virt.rosypeony128.chatgpt.site/)** · **[Open the stellar workspace](https://holmesnet-virt.rosypeony128.chatgpt.site/systems.html)**

## October 23 update — GUPPI refinement and Sol explorer

**[Meet GUPPI](https://holmesnet-virt.rosypeony128.chatgpt.site/guppi.html)** · **[Watch the corrected greeting](../assets/guppi/greeting-review.mp4)** · **[Explore Sol](https://holmesnet-virt.rosypeony128.chatgpt.site/sol.html)**

GUPPI now has an initial animated 3D model based on Quaternius's CC0 Universal Base Characters. Jason approved Concept 03: long curls, warm brown skin, a natural athletic build, and a graphite command uniform with a cream yoke and bronze trim. The approved concept remains the visual target; the 3D likeness is still being refined.

The October 23 refinement softens the face, improves the uniform panel and trim, and corrects the greeting. The hand raises with the palm forward and elbow below the shoulder, waves, and returns to rest. Sleeve-cuff weights follow the bending sleeve. Greeting playback runs once and supports replay.

### GUPPI — from approved concept to animated character

| Approved Concept 03 | Current 3D refinement |
|---|---|
| <img src="../assets/guppi/concept-03.png" alt="Approved GUPPI Concept 03 character design" width="420"> | <img src="../assets/guppi/rig-front.png" alt="GUPPI refinement 02 full-body model render" width="420"> |

*Concept 03 is the design target. Refinement 02 is the working 3D model; likeness polish remains underway.*

[![Watch GUPPI's corrected greeting — four-second video](../assets/guppi/greeting-poster.png)](../assets/guppi/greeting-review.mp4)

**[▶ Watch the greeting — 4 seconds (MP4)](../assets/guppi/greeting-review.mp4)** · [Open the interactive studio](https://holmesnet-virt.rosypeony128.chatgpt.site/guppi.html)

*Click the preview to play the exported-animation review: raise, palm-forward wave, and return to rest. This is a rendered motion review, not browser gameplay footage.*

### Face and uniform detail

| Portrait | Rear view |
|---|---|
| <img src="../assets/guppi/rig-portrait.png" alt="Refinement 02 face, collar and cream uniform yoke" width="420"> | <img src="../assets/guppi/rig-back.png" alt="Refinement 02 rear uniform and long ponytail" width="420"> |

*Actual model renders show the face, uniform and hair from complementary views. These images document the current pass rather than final visual acceptance.*

The model contains 65 joints and four clips: Idle, Listening, Explaining and Greeting. Export validation checked finite geometry at 20 samples across the four clips, palm orientation and wrist/elbow placement during the wave, and matching start/end landmarks. The selected automated suite passed 30 tests, including one-shot greeting and replay behavior. Browser WebGL was unavailable, so interactive GPU playback and real phone/PC performance remain unverified.

The October 22 Sol explorer adds textured previews of the Sun, eight planets and Moon. Detail textures load on demand; optional Milky Way backgrounds load only when enabled. Body sizes, orbit spacing/phases and lighting are illustrative, not an ephemeris or new campaign evidence.

### Next work

- Review likeness, uniform trim, hair and greeting deformation against Concept 03 on phone and desktop.
- Refine facial expressions; implement voice, lip-sync and the live assistant connection.
- Resume the book-inspired VIRT menus and screens after GUPPI review.

Concept approval does not mean the current 3D likeness has final acceptance. The uploaded version 1 captures remain historical evidence, separate from refinement 02.

## Why build this?

HolmesNet began as a documented expedition through Bobiverse: Replicant Too. VIRT explores how a virtual command environment can make a growing campaign easier to understand: where our replicants are assigned, what is moving between systems, and which decisions still need evidence.

The longer-term goal is to explore similar interfaces for engineering projects, autonomous systems and operational management. That is a development direction, not a claim that this game prototype is ready for real-world control.

## Development stages

| Stage | Outcome |
|---|---|
| Architecture | Approved room proportions, viewpoints, sightlines and circulation. |
| Functional Prototype 1 | Navigable room, console records, filters, roster search and prepared briefings. |
| Visual design | Warm wood and earth tones with a mountain outlook. |
| Runway treatment | Photorealistic visual reference and concept motion; the live cinematic view composites functional displays over a still. |
| Stellar atlas | Three.js navigation and 1,568 HYG catalog stars within 60 light-years. Systems-map direction approved October 18. |
| Console rollout — v0.6 | Six station-specific stellar workspaces, operational layers and Map/Analysis modes. Catalog projections now appear on room displays. Device review remains open. |

## Screenshots and demonstration

![HolmesNet stellar atlas](https://holmesnet-virt.rosypeony128.chatgpt.site/media/stellar-atlas-2026-10-18.png)

*Jason's October 18 capture of the approved Systems-map prototype: catalog positions, system selection and dated campaign records.*

![HolmesNet mountain command room](https://holmesnet-virt.rosypeony128.chatgpt.site/media/command-room-2026-10-18.png)

*Jason's October 18 capture of the Runway-inspired room implementation. This records v0.5, before the October 19 console rollout.*

**[Watch the 20-second walkthrough excerpt](https://holmesnet-virt.rosypeony128.chatgpt.site/media/virt-walkthrough-excerpt.mp4)**

The excerpt shows the interactive room in the October 18 recording. It is silent and trimmed from the supplied implementation video; it is not a live feed or footage of the later rollout.

## Each console has a purpose

| Console | Operational view |
|---|---|
| Systems | Operating systems, recorded infrastructure and deferred destinations. |
| Missions | Deferred beam objectives and separately identified supply freight. No invented beam dispatches. |
| Replicants | Last-confirmed system assignments, roles and groups, with resident search. |
| Logistics | Recorded freight corridors, cargo totals, remaining times and system-level infrastructure layers. |
| Archives | Evidence coverage and dated historical milestones. |
| Command | Network summary, residents, freight and future objectives. |

Choose **Open stellar workspace** from a console to use its 3D map. The station and selected system carry into the workspace. Compact console panels retain an accessible schematic fallback.

## Evidence and limitations

- Catalog coordinates are HYG J2000.0 astronomical context, not verified game geometry or positions propagated to game year 2184.
- Alpha Centauri uses its primary star as the representative marker, not the system barycenter.
- Replicant positions mean last-confirmed system assignments. Exact vessel and facility coordinates are unknown.
- Freight lines show recorded connections. Remaining travel times are frozen checkpoint values.
- System inventory is dated January 20, 2184; assignments and freight are confirmed through February 20, 2184. Historical hold cargo has its own earlier date.
- The cinematic room is a composited still with functional overlays. The separate navigable room uses simplified geometry.
- No live game synchronization, autonomous orders or headset validation is claimed.
- The October 19 atlas milestone passed 29 checks; the October 23 selected suite passed 30, including greeting playback. These counts describe different milestone suites. Full browser/GPU and phone/PC testing remains open.

## Credits and reuse

**Bobiverse: Replicant Too** was created by **[u/damiankw](https://www.reddit.com/user/damiankw/)**. **[Play the original game](https://replicate.anek.online/)**. Dennis E. Taylor created the Bobiverse books and setting. HolmesNet is an independent fan project intended to encourage discovery of the game and document constructive gameplay observations.

Three.js is MIT licensed. The adapted HYG v4.1 star dataset credits David Nash / Astronexus and is distributed under CC BY-SA 4.0. [Dataset and transformation notes](https://holmesnet-virt.rosypeony128.chatgpt.site/data/README.md). Runway supplied the architectural treatment; the screenshots and demonstration are Jason's project captures.

GUPPI's base character is by Quaternius (CC0); custom character changes build on that foundation. [Asset notes and attribution](../assets/guppi/README.md). Solar System Scope / INOVE textures are used under CC BY 4.0; [per-asset provenance](https://holmesnet-virt.rosypeony128.chatgpt.site/textures/sources.json) records sources and resized derivatives. Some source colors are enhanced and terrain is fictional.

The campaign companion source lives in this repository. The newer VIRT application is deployed separately; this page documents and links to that working application.
