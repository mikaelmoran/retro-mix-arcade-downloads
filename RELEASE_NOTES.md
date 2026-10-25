# Retro Mix Arcade 1.6.1

This update follows a full visual, autonomous-play, and full-size rendering
review of all twelve screen saver games.

- Streamlined the shared CRT overlay by drawing its bright and dark speckles
  in batches and sampling the RGB split without creating a color object for
  every sample.
- Reduced per-frame drawing overhead in Tank Duel, Breakout, Garden Swarm,
  and River Crossing while keeping their existing artwork and effects.
- Rechecked all twelve games at 2560 × 1440, 70 full-size game switches,
  the effects and preview windows, and extended autonomous-play simulations.

The largest render costs still come from Vectoroid and Sprint 2 at high
resolution. Frame rate depends on display resolution and enabled effects.

## Installation

1. Expand the macOS ZIP and move `Retro Mix Arcade.app` to Applications,
   replacing the previous copy.
2. Open the app once, then choose **Retro Mix Arcade** in **System Settings →
   Wallpaper → Screen Saver**.

Requires macOS 14 or newer. The app contains Apple Silicon and Intel code.
Existing JMR unlock codes remain valid. The archive is locally signed for
development and is not notarized by Apple.
