# Retro Mix Arcade 1.2.10

Vectoroid now draws its game frames into a retro-resolution layer that macOS
scales for the display. In the 2560 × 1440 capture benchmark, average frame
time fell from about 100 ms to about 72 ms with all 60 effects enabled.
The AI game still follows real elapsed time when drawing takes longer.

The layer was checked in the live macOS screen saver, and the automated
switching test covered 36 full-size game changes without a black frame.

The six AI games, Mixed mode, and existing JMR unlock codes remain available.

## Installation

1. Expand the macOS ZIP and move `Retro Mix Arcade.app` to Applications,
   replacing the previous copy.
2. Open the app and click **Save selection**.
3. In **System Settings → Wallpaper → Screen Saver**, choose
   **RetroMixModern**.

Requires macOS 14 or newer. The app contains Apple Silicon and Intel code.
The [$5 JMR unlock item](https://buymeacoffee.com/mikaelmoran/e/585964)
remains available.

This archive is locally signed for development. For a smooth installation on
other Macs, a Developer ID signed and notarized archive is required.
