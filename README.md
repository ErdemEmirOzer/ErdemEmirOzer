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

### [NEBULA](https://github.com/ErdemEmirOzer/Nebula)

<p align="center">
  <a href="https://github.com/ErdemEmirOzer/Nebula">
    <img src="https://raw.githubusercontent.com/ErdemEmirOzer/Nebula/main/docs/brand/nebula-cover.png" width="100%" alt="NEBULA key art" />
  </a>
</p>

A private-alpha space exploration, extraction, logistics, and territorial-control game built with Unity and C#. Its portfolio snapshot exposes the engineering work while keeping playable builds and provenance-gated production assets private.

- Deterministic galaxy generation with FNV-1a hashing and reproducible world IDs
- Full, Warm, and sparse system streaming with remote simulation and floating-origin precision
- Extraction, processing, structures, fleet logistics, combat, progression, tutorials, and versioned saves
- Explicit composition root, typed runtime context, lifecycle ownership, and modular domain architecture
- 491 runtime files and 375 EditMode/PlayMode test files in the documented snapshot

**Stack:** Unity 2022 LTS · C# · NUnit · deterministic simulation · procedural generation

[Source showcase](https://github.com/ErdemEmirOzer/Nebula) · [Architecture](https://github.com/ErdemEmirOzer/Nebula/blob/main/docs/ARCHITECTURE.md) · [Algorithms](https://github.com/ErdemEmirOzer/Nebula/blob/main/docs/ALGORITHMS.md) · [Features](https://github.com/ErdemEmirOzer/Nebula/blob/main/docs/FEATURES.md)

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
