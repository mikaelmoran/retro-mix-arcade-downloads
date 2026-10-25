# Retro Mix Arcade 1.4.0

Three more autonomous games join the screen saver, bringing the total to ten:

- **Missile Defense**, inspired by Missile Command: three AI batteries prioritize
  threats and launch interceptors to protect six cities. Later waves introduce
  splitting missiles and a faster attack pace.
- **Star Squadron**, inspired by Galaga: alien formations move and dive while
  an AI pilot tracks targets, fires, and survives enemy shots.
- **Maze Chase**, inspired by Pac-Man: a self-playing runner collects pellets
  through newly generated mazes while four hunters chase, scatter, and retreat
  during power phases.

Each game has 60 selectable effects, including Sprint's shared CRT controls and
its own game-specific visuals. All three appear in the live app preview, the
System Settings Options sheet, and Mixed rotation. Existing Mixed selections
migrate automatically. The new app preview thumbnails and gameplay captures
come from the running screen saver.

Automated play ran each new game for 300 simulated seconds. Full-size tests
passed 60 game switches and transition frames without black screens. At
2560 × 1440, the new games averaged about 15–22 ms per frame on the
development Mac; actual performance depends on the display and enabled effects.

## Installation

1. Expand the macOS ZIP and move `Retro Mix Arcade.app` to Applications,
   replacing the previous copy.
2. Open the app once, then choose **Retro Mix Arcade** in **System Settings →
   Wallpaper → Screen Saver**.

Requires macOS 14 or newer. The app contains Apple Silicon and Intel code.
Existing JMR unlock codes remain valid. The archive is locally signed for
development and is not notarized by Apple.
