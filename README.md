<div align="center">
  <h1>Erdem Emir Özer</h1>
  <p><strong>Game Developer · Gameplay Systems · Deterministic Simulation</strong></p>
  <p>I build system-driven games with Unity/C# and native iOS experiences with Swift.</p>
</div>

## Selected projects

### [DEATHS DEMOLITION](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/deaths-demolition/README.md)

<p align="center">
  <a href="https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/deaths-demolition/README.md">
    <img src="https://raw.githubusercontent.com/ErdemEmirOzer/ErdemEmirOzer/main/projects/deaths-demolition/images/hero.jpg" width="100%" alt="Deaths Demolition key art" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/deaths-demolition/README.md">
    <img src="https://raw.githubusercontent.com/ErdemEmirOzer/ErdemEmirOzer/main/projects/deaths-demolition/images/gameplay-crowd-hud.jpg" width="32%" alt="Deaths Demolition: Hard mode crowd fight with HUD" />
    <img src="https://raw.githubusercontent.com/ErdemEmirOzer/ErdemEmirOzer/main/projects/deaths-demolition/images/gameplay-barrage.jpg" width="32%" alt="Deaths Demolition: Barrage full-auto rockets" />
    <img src="https://raw.githubusercontent.com/ErdemEmirOzer/ErdemEmirOzer/main/projects/deaths-demolition/images/ui-run-tree.jpg" width="32%" alt="Deaths Demolition: the run tree screen" />
  </a>
</p>

A top-down wave-survival zombie shooter built with Unity and C#. The player holds an old Japanese palace compound against crowds of up to 40 zombies, while a feature-based upgrade tree turns ordinary weapons into absurd ones round by round. It is in active development and has just closed its final revision round; the source and builds are private, and the project page shows the game and the engineering behind it.

- Ten classic weapons, two chain-reaction Specials and ten wall-buy stations on one zero-allocation projectile simulation (256 live projectiles, fixed 120 Hz step)
- A 7-branch run tree (63 nodes, 7 alternative capstones, 10 synergies) and an Awakening meta page that buys variety, not power
- Normal, Hard and Demolition modes; four zombie tiers, five attack styles and chase / intercept / cut pursuit roles
- A code-built palace world with 130 lanterns, twelve interiors, ~60k GPU-instanced plants and after-rain lighting; 7.5 ms per frame on High at 40 zombies (M1 Pro, 1080p)
- About 487k lines of C# and 3,591 automated test cases, with scripted integration, compile, CI and acceptance gates

**Stack:** Unity 2022.3 LTS · URP 14 · C# · NUnit · Input System · AI Navigation · Blender pipeline

[Project page](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/deaths-demolition/README.md) · [Screenshots](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/deaths-demolition/README.md#screenshots) · [Arsenal](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/deaths-demolition/README.md#arsenal) · [Architecture](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/deaths-demolition/README.md#architecture) · [Production pipeline](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/deaths-demolition/README.md#production-pipeline)

---

### [NEBULA](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/nebula/README.md)

<p align="center">
  <a href="https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/nebula/README.md">
    <img src="https://raw.githubusercontent.com/ErdemEmirOzer/ErdemEmirOzer/main/projects/nebula/images/hero.jpg" width="100%" alt="NEBULA key art" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/nebula/README.md">
    <img src="https://raw.githubusercontent.com/ErdemEmirOzer/ErdemEmirOzer/main/projects/nebula/images/gameplay-blackhole-aetheria.jpg" width="32%" alt="NEBULA: the ship at a galaxy's black hole with the flight HUD" />
    <img src="https://raw.githubusercontent.com/ErdemEmirOzer/ErdemEmirOzer/main/projects/nebula/images/map-universe-diagonal.jpg" width="32%" alt="NEBULA: the whole universe on the strategic map" />
    <img src="https://raw.githubusercontent.com/ErdemEmirOzer/ErdemEmirOzer/main/projects/nebula/images/page-resources.jpg" width="32%" alt="NEBULA: the Resources page of the command menu" />
  </a>
</p>

A single-player space game built with Unity and C#. The player flies one ship by hand across a deterministic universe of four galaxies, scans and drills planets, processes what they yield, builds command posts and defenses, and holds planets against raids, with a support fleet carrying the work further. It is in private alpha; the source is public as a portfolio snapshot, and builds and production assets stay private.

- A deterministic universe of four galaxies from one seed, revealed through signal → located → visited knowledge, with Full / Warm / 1 Hz sparse streaming and remote simulation of the systems you are not in
- Scan, drill, process and build: 5 resource families and 5 rarities, structures with real lifecycles and reserved costs, and planetary control that needs a 120-second stabilisation
- Scouts, Collectors, Engineers and Escorts with Mk tiers, orbital logistics, and shield / armour / hull combat with Laser, Plasma and EM hardpoints
- Levels 1–100, 12 ship modules in four branches, an 11-chapter tutorial of 176 steps, and three save slots with rotating backups and migrations up to schema v15
- About 124k lines of runtime and editor C# and 3,857 test declarations behind a four-lane PlayMode gate; the release player cut from 3.47 GiB to 613 MiB

**Stack:** Unity 2022.3 LTS · C# · built-in render pipeline · NUnit · glTFast · deterministic simulation · procedural generation

[Project page](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/nebula/README.md) · [Screenshots](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/nebula/README.md#screenshots) · [Black holes and other systems](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/nebula/README.md#beyond-the-home-system) · [Strategic map](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/nebula/README.md#strategic-map) · [Architecture](https://github.com/ErdemEmirOzer/ErdemEmirOzer/blob/main/projects/nebula/README.md#architecture) · [Source snapshot](https://github.com/ErdemEmirOzer/Nebula)

---

### [ChessGame](https://github.com/ErdemEmirOzer/ChessGame)

<p align="center">
  <a href="https://github.com/ErdemEmirOzer/ChessGame">
    <img src="https://raw.githubusercontent.com/ErdemEmirOzer/ChessGame/main/docs/screenshots/main-menu.jpg" width="31%" alt="ChessGame main menu" />
    <img src="https://raw.githubusercontent.com/ErdemEmirOzer/ChessGame/main/docs/screenshots/game-board.jpg" width="31%" alt="ChessGame board" />
  </a>
</p>

A native iOS chess prototype with a UIKit board, persistent game state, and computer opponent.

- Minimax search with alpha-beta pruning and material-based evaluation
- Legal move generation for every standard chess piece
- UIKit presentation with Core Data persistence
- Documented game flow, architecture, and AI decision pipeline

**Stack:** Swift · UIKit · Core Data · XCTest · minimax · alpha-beta pruning

[Repository](https://github.com/ErdemEmirOzer/ChessGame) · [Architecture and algorithms](https://github.com/ErdemEmirOzer/ChessGame#architecture)

## Engineering focus

`Gameplay architecture` · `Deterministic systems` · `AI and search` · `Real-time rendering` · `Persistence` · `Testing` · `Developer tooling`
