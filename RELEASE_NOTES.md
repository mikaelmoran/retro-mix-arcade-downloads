# Retro Mix Arcade 1.5.0

This release substantially rebuilds the three newest screen saver games while
keeping Retro Mix Arcade's monochrome CRT style and existing effect controls.

- **Missile Defense:** Six cities now persist between waves. Three batteries
  have limited ammunition and can be destroyed. Later waves add splitting and
  evasive missiles. The AI predicts intercept points, prioritizes threats,
  and earns bonuses for surviving cities and unused ammunition. Incoming
  trails, targeting marks, and expanding blasts are easier to follow.
- **Star Squadron:** Distinct enemy types enter formation, peel off on curved
  dives, and return smoothly. Bosses have tougher hulls and can use a tractor
  beam; the AI can rescue a captured fighter and fire with two ships. Shot
  dodging, explosion sprites, and challenge waves add variety.
- **Maze Chase:** A mirrored maze now includes a ghost house, side tunnel,
  four hunters with different targets, alternating chase and scatter periods,
  frightened behavior, bonus fruit, and lives. The runner routes around the
  ghost house, clears pellets, pursues frightened ghosts, and starts another
  round. Independent motion timing keeps all four ghosts moving smoothly;
  animated hems, directional eyes, returning ghost eyes, a timed chomping
  mouth, and a closing death animation give the characters more life.

In repeated five-minute simulations, the missile AI cleared at least 14
waves, the squadron pilot completed at least 15 waves, and the maze runner
cleared at least five boards. Full-size switching and render tests passed on
the development Mac; actual speed depends on the display and enabled effects.

## Installation

1. Expand the macOS ZIP and move `Retro Mix Arcade.app` to Applications,
   replacing the previous copy.
2. Open the app once, then choose **Retro Mix Arcade** in **System Settings →
   Wallpaper → Screen Saver**.

Requires macOS 14 or newer. The app contains Apple Silicon and Intel code.
Existing JMR unlock codes remain valid. The archive is locally signed for
development and is not notarized by Apple.
