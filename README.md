<h1 align="center">Cem Yılmaz</h1>

<p align="center">
  <b>Lead Unity Developer</b> · Unity DOTS (ECS · Jobs · Burst) · Compute Shaders / GPGPU · Mobile
</p>

<p align="center">
  <a href="https://cemtas81.github.io/">Portfolio &amp; playable demos</a> ·
  <a href="https://www.linkedin.com/in/cem-y%C4%B1lmaz-870501114">LinkedIn</a> ·
  <a href="https://cemtas81.github.io/Cem_Yilmaz_CV%20(1).pdf">CV (PDF)</a> ·
  <a href="mailto:cemtas81@gmail.com">cemtas81@gmail.com</a>
</p>

6+ years building Unity games for mobile, PC, WebGL, VR and interactive kiosks. I lead a 7-person team at **Bleis Interactive**, owning architecture, code reviews, performance and Google Play / App Store releases for four mobile titles.

## Commercial work and code review

My production work — Unity DOTS (ECS, Job System, Burst) and Compute Shader / GPGPU systems, plus shipped mobile games — is commercial and kept in private repositories. **For a technical assessment I can walk through that code live (screen share) or share a code-only excerpt on request.** The public repositories on this page are side projects, prototypes and learning experiments.

## Performance at scale

| Project | Details |
|---|---|
| **3,000,000+ RTS units on the GPU**<br><sub>Compute Shaders · C#</sub> | Units and projectiles simulated and animated entirely on the GPU, with full RTS selection and control. Logic moved from ECS to compute shaders for another order of magnitude in scale. · [r/Unity3D post](https://www.reddit.com/r/Unity3D/comments/1r6a1ho/3_million_interactive_units_moving_from_ecs_to/) |
| **75,000+ animated NPCs**<br><sub>ECS · Job System · Burst</sub> | NPC framework built for the Unity Asset Store, handling 75,000+ animated enemies with complex logic (shown at the 50K milestone). · [r/Unity3D post](https://www.reddit.com/r/Unity3D/comments/1q1g3kj/50000_animated_enemies_massive_update_to_my_dots/) |
| **1,000-enemy open-world hack & slash**<br><sub>NavMesh · DOTS</sub> | Fast-paced action prototype running up to 1,000 enemies with navigation and avoidance without dropping frames. · [Video](https://www.youtube.com/watch?v=31aKcRl42ig) |

## Shipped work

- **10+ mobile games** on Google Play — [Gorilli Games](https://play.google.com/store/apps/developer?id=Gorilli+Games)
- **Bleis Interactive** mobile titles — [Google Play](https://play.google.com/store/apps/developer?id=Bleis+Interactive) · [App Store](https://apps.apple.com/tr/developer/bleis-interactive-insaat-otomotiv-danismanlik-ticaret/id6805367103)
- **5 museum projects** for the Gallipoli Historical Site — VR tour and interactive kiosks (iOS, Android, VR, kiosk)
- **Play in the browser:** [Dye Hard](https://cemtas81.github.io/DyeHard/) · [AquaSort](https://cemtas81.github.io/AquaSort/) · [Jigsaw Puzzle](https://cemtas81.github.io/JigsawPuzzle/) · [Showreel](https://www.youtube.com/watch?v=0_pbJQ1nvWg)

## Selected public repositories

Side projects and prototypes — see the note above about commercial work.

| Repository | Highlights |
|---|---|
| [3DArcher Multiplayer](https://github.com/cemtas81/3DArcher-Multiplayer-using-netcode-relay) | Netcode for GameObjects · Unity Relay / Lobby · server-side arrow physics with client-side visual interpolation · ballistic trajectory preview · networked object pooling |
| [2D RTS](https://github.com/cemtas81/2dRts) | Heap-based A* pathfinding · unit selection and move/attack orders · grid building placement · object pooling |
| [Color Maze](https://github.com/cemtas81/ColorMaze) | 3D maze puzzle built for PC/Steam (unreleased) · data-driven levels · time bonus/penalty mechanics · PlayFab login and leaderboard · skin shop |
| [damage-numbers-DOTS](https://github.com/cemtas81/damage-numbers-DOTS/commit/37cf9a1031f4b9486ee9fc749636686c42a03855) | Fix for a TempJob `EntityCommandBuffer` leak in an ECS system |

## Tech

**Engine & languages:** Unity 6 · C# · HLSL  
**Performance:** DOTS (Entities, Job System, Burst) · Compute Shaders / GPGPU · profiling & optimization  
**Architecture:** SOLID · data-oriented design · Zenject · UniTask  
**Multiplayer & services:** Netcode for GameObjects · Relay / Lobby · PlayFab · Addressables  
**Platforms:** Android · iOS · PC · WebGL · VR / AR · interactive kiosks  
**Also:** Shader Graph · ML-Agents · Unreal Engine · Git · Agile / Scrum · Claude Code · Cursor
