# Retro Mix Arcade 1.6.2

This update improves full-size rendering for the games that were most expensive
at 2560 × 1440.

- Vectoroid now draws directly at display resolution and reuses its CRT grille
  geometry. Its measured render time fell from about 45 ms to 37 ms per frame.
- Garden Swarm and River Crossing use a precomposited field color while keeping
  their existing appearance. Garden Swarm fell from about 33 ms to 24 ms.
- Sprint 2 reuses its scanline geometry. Its current full-size render remains
  around 33–35 ms on the development Mac.
- Rechecked all twelve games, 70 full-size game switches, nonblack frames,
  autonomous play, Vectoroid timing, and effect synchronization.

These numbers are synchronous render measurements on one Mac, not a guaranteed
screen saver frame rate. Display resolution and enabled effects still matter.

## Installation

1. Expand the macOS ZIP and move `Retro Mix Arcade.app` to Applications,
   replacing the previous copy.
2. Open the app once, then choose **Retro Mix Arcade** in **System Settings →
   Wallpaper → Screen Saver**.

Requires macOS 14 or newer. The app contains Apple Silicon and Intel code.
Existing JMR unlock codes remain valid. The archive is locally signed for
development and is not notarized by Apple.
