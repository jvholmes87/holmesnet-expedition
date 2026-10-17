# HolmesNet Expedition

**From one factory to four systems.** An independent fan campaign and mobile/desktop companion for [Bobiverse: Replicant Too](https://replicate.anek.online).

![Songtan Labs — HolmesNet Expedition](assets/banner.jpg)

**[Open the interactive companion](https://jvholmes87.github.io/holmesnet-expedition/)** · **[Read Expedition 001 on X](https://x.com/jasonvonholmes/status/2111452094502977841)** · [Campaign instructions](docs/first-expedition.md) · [Evidence and limitations](docs/evidence.md) · [Campaign JSON](data/campaign.json)

Created by **Jason Von Holmes / Songtan Labs**. This project connects 15 years of Air Force engineering experience, a computer science degree and graduate IT studies with a systems engineering focus: plan, observe, document and improve.

## V0.1 companion

- Select systems on a keyboard-accessible schematic map.
- Inspect local inventory and installed infrastructure.
- Search the six-person roster and filter by assignment group.
- Review completed, active and deferred missions.
- Sort nine freight flights by arrival proximity, destination or cargo.
- Explore a dated campaign timeline and prepared MAAT briefings.
- Download the campaign JSON and roster CSV.

Static HTML/CSS/JavaScript. No package installation, build step, API key or account is needed to run it. All assets load locally. This is a manual campaign snapshot; it does not control or synchronize with the game. The map is a labelled schematic, not an astronomical coordinate plot or SCUT range calculation. Personal VIRT is deferred.

## Current campaign checkpoint

**February 20, 2184:** four operating systems, six replicants, 77 roamers, 24 total freighters and nine flights. Global stored stock: **80,095 parts / 653,992 ore**.

| System | Team | Campaign assignment |
|---|---|---|
| Epsilon Eridani | Holmes + Mary | Home command and industry |
| Sol | Octavia | Resident Bob support |
| Alpha Centauri | Mae | Resident Bob support |
| Tau Ceti | Banneker + Katherine | SEED-01 physical expedition |

System inventories are dated **January 20, 2184**, one month earlier than the global header. Historical cargo holds are dated **August 9, 2174**. Each view keeps those distinctions visible.

Future missions **BEAM-DELTA-01** and **BEAM-GL54-01** are deferred to another gameplay session. Jason reports that beaming to Delta Eridani and Gliese 54 is available; resident choices and current quotes remain pending. Neither destination is counted as an operating player system.

## Run locally

From this folder:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`. Use a local server because the app loads its JSON with `fetch`.

## Publish on GitHub Pages

1. Place `index.html`, `styles.css`, `app.js`, `.nojekyll`, and the `assets`, `data`, and `docs` directories at the repository root.
2. In **Settings → Pages**, choose **Deploy from a branch**.
3. Choose the **main** branch and **/(root)**, then save.
4. Wait for the Pages deployment to finish and use the actual URL shown by GitHub.

Reference: GitHub. (n.d.). *[Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).* No live Pages URL is claimed until deployment is verified.

## Update the campaign

Edit `data/campaign.json`, keeping dates and evidence sources with each snapshot. Update `data/replicant_roster.csv` when roster observations change. Keep planned work distinct from completed actions. Do not reinterpret a request's dispatch credit as physical cargo delivery.

## Credits and reuse

Game: **Bobiverse: Replicant Too**, by its developer and contributors. The Bobiverse setting and characters belong to their respective rights holders. This project is independent and has no claimed endorsement.

The avatar and banner were generated for Jason's Songtan Labs / HolmesNet identity with OpenAI image generation. This repository does not include game source code or a licensed game-asset pack. The app uses browser APIs and system fonts without external runtime libraries. No blanket license is applied to game content or screenshots. Reuse terms for the original project code remain to be selected by the owner.

## Verification

JavaScript syntax, campaign schema/counts, relative file references, route switching, system selection, roster filtering, logistics sorting and prepared-briefing toggle were checked during source preparation. Real phone rendering and live Pages deployment still require verification after hosting.
