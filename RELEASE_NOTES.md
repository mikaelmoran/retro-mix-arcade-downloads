# Retro Mix Arcade 1.2.19

The six autonomous games now make more deliberate, human-like decisions.
Sprint drivers hold an overtaking line briefly instead of changing their minds
every frame. Vectoroid's pilot selects threats, dodges approaching rocks, and
fires in bursts. Pong players revise their estimate of the ball's landing and
choose a shot before contact. Light Cycles riders have different risk levels
and balance open space with pressure on the opponent. Tank Duel opponents aim
from recent sightings with small corrections. Breakout's paddle reads the
incoming balls in short intervals and chooses a brick lane for its return.

These are rule-based computer players. Their reaction times and mistakes are
bounded so games continue to move and score.

Automated gameplay checks passed for all six games. The full-size test passed
36 switches between games with no black frames. Rendering at 2560 × 1440
remained comparable to the previous release on the development Mac.

## Installation

1. Expand the macOS ZIP and move `Retro Mix Arcade.app` to Applications,
   replacing the previous copy.
2. Open the app once, then choose **Retro Mix Arcade** in **System Settings →
   Wallpaper → Screen Saver**.

Requires macOS 14 or newer. The app contains Apple Silicon and Intel code.
Existing JMR unlock codes remain valid. The archive is locally signed for
development and is not notarized by Apple.
