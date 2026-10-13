# Retro Mix Arcade 1.2.16

Breakout now moves faster and has more action. The AI paddle predicts which
ball will land next and aims its return at bricks still on screen. Brick hits
trigger three-ball bursts, and each cleared level starts a new brick pattern.
Faster balls use smaller collision steps so they still register brick and
paddle hits. The CRT effects remain available for every game.

The updated game passed five extended simulations, including multi-ball play,
misses, and level changes. The app smoke test, effect sync test, 36 full-size
game switches, and a 2560 × 1440 render benchmark also passed. Breakout's
composited benchmark averaged 32.6 ms per frame on the development Mac;
actual speed depends on the display and enabled effects.

## Installation

1. Expand the macOS ZIP and move `Retro Mix Arcade.app` to Applications,
   replacing the previous copy.
2. Open the app once, then choose **Retro Mix Arcade** in **System Settings →
   Wallpaper → Screen Saver**.

Requires macOS 14 or newer. The app contains Apple Silicon and Intel code.
Existing JMR unlock codes remain valid.

This archive is locally signed for development and is not notarized by Apple.
