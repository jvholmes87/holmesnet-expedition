# VIRT development — From architecture to operational maps

Updated October 19, 2026 · Jason Von Holmes / Songtan Labs

**[Enter VIRT](https://holmesnet-virt.rosypeony128.chatgpt.site/)** · **[Open the stellar workspace](https://holmesnet-virt.rosypeony128.chatgpt.site/systems.html)**

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
- 29 automated checks pass; syntax checks and rendered room-screen inspection also completed. Full browser/GPU and phone/PC testing remains open.

## Credits and reuse

**Bobiverse: Replicant Too** was created by **[u/damiankw](https://www.reddit.com/user/damiankw/)**. **[Play the original game](https://replicate.anek.online/)**. Dennis E. Taylor created the Bobiverse books and setting. HolmesNet is an independent fan project intended to encourage discovery of the game and document constructive gameplay observations.

Three.js is MIT licensed. The adapted HYG v4.1 star dataset credits David Nash / Astronexus and is distributed under CC BY-SA 4.0. [Dataset and transformation notes](https://holmesnet-virt.rosypeony128.chatgpt.site/data/README.md). Runway supplied the architectural treatment; the screenshots and demonstration are Jason's project captures.

The campaign companion source lives in this repository. The newer VIRT application is deployed separately; this page documents and links to that working application.
