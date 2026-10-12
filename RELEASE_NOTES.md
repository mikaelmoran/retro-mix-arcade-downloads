# Retro Mix Arcade 1.2.15

Vectoroid now animates more smoothly in the full screen saver. Its faint
phosphor trails use lighter drawing operations, vector outlines reuse their
paths, and the rendering buffer scales down for small previews. The CRT look
and all effect controls remain available.

On the development Mac, the full-screen Vectoroid extension used about 70%
of one CPU core after this change, down from roughly 100%. A 2560 × 1440
composited frame benchmark improved from about 71 ms to 53 ms. Actual speed
depends on the Mac, display, and enabled effects.

The animation timing check, 36 full-size game switches, app smoke test, and
screen saver capture passed.

## Installation

1. Expand the macOS ZIP and move `Retro Mix Arcade.app` to Applications,
   replacing the previous copy.
2. Open the app once, then choose **Retro Mix Arcade** in **System Settings →
   Wallpaper → Screen Saver**.

Requires macOS 14 or newer. The app contains Apple Silicon and Intel code.
Existing JMR unlock codes remain valid.

This archive is locally signed for development and is not notarized by Apple.
