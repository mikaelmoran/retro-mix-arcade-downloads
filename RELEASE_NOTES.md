# Retro Mix Arcade 1.7.0

All twelve games now pass through the Sprint 2 display renderer, giving them
the same monochrome pixel grid, CRT frame, curved glass, scanlines, and shared
screen and phosphor effects. Game-specific effects remain individually
configurable.

Open **Effects → Shared CRT / Sprint 2** to choose the shared effects and
strength, then save. The live preview and screen saver use those settings.

The shared rendering is more demanding than the previous display path for
some games. On the development Mac, synchronous full-size image captures at
2560 × 1440 measured approximately 36–40 ms per frame. Actual screen saver
performance varies with the Mac, display resolution, and enabled effects.

## Installation

1. Expand the macOS ZIP and move `Retro Mix Arcade.app` to Applications,
   replacing the previous copy.
2. Open the app once, then choose **Retro Mix Arcade** in **System Settings →
   Wallpaper → Screen Saver**.

Requires macOS 14 or newer. The app contains Apple Silicon and Intel code.
Existing JMR unlock codes remain valid. The archive is locally signed for
development and is not notarized by Apple.
