# MythosMaphack release notes

## 0.1.0-preview

First preview, for testers.

- **Map window.** The full layout of the level you are in: walls, exits labelled with where they lead, stairs and
  cave entrances, waypoints, shrines, wells, super chests, quest objects and bosses.
- **Live units.** You, other players and monsters, updated ten times a second.
- **Views.** Automap (45°) or top-down; Follow, Fit, drag to pan, mouse wheel to zoom, double-click to follow again.
- **On top**, and a picker when more than one game is running.
- **Preview mode** for trying the map without the game: `MythosMaphack.exe --preview 054ca669 3 0`
  (seed, level number, difficulty 0/1/2).
- Works with Diablo II: Resurrected **3.3.93847** only; any other game version shows "not supported".

**Known limits of this preview**

- Not yet tested against a live game. Finding the map seed in the running game is the part being tested: if the
  status bar stays on "seed unresolved", the map cannot be drawn yet. Please report it on Discord with the level
  you were in.
- In a game with other players, it may follow the wrong player.
- Not code-signed: Windows may show "Windows protected your PC". Choose **More info → Run anyway**.
