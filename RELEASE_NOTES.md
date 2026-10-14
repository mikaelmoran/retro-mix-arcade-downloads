# Retro Mix Arcade 1.2.18

All six games now share a more active CRT presentation. Collisions, blasts,
brick hits, and score moments pulse the display frame. A live channel
indicator and animated signal sweep make every game feel like part of the same
arcade broadcast. These animations follow the existing Sprint glow, signal
sweep, brightness, and intensity settings.

Mixed mode has a stronger tuning transition with a brighter channel beam,
short signal ghosts, and a lock indicator. The six gameplay captures and app
preview images have been refreshed from the running games.

The full-size test passed 36 game switches, including mid-transition frames
with no black screen. The app smoke test passed. At 2560 × 1440, the six
composited render benchmarks stayed close to the previous version on the
development Mac; actual speed depends on the display and enabled effects.

## Installation

1. Expand the macOS ZIP and move `Retro Mix Arcade.app` to Applications,
   replacing the previous copy.
2. Open the app once, then choose **Retro Mix Arcade** in **System Settings →
   Wallpaper → Screen Saver**.

Requires macOS 14 or newer. The app contains Apple Silicon and Intel code.
Existing JMR unlock codes remain valid. The archive is locally signed for
development and is not notarized by Apple.
