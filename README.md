# Sixes Blitz

An original six-a-side cricket game for the browser. Bat and bowl five-over
innings and win a three-round knockout cup.

- `index.html` is the 2D game: markup, styles and script in one file,
  drawn on a plain canvas. No dependencies apart from two web fonts.
- `3d.html` is the same game rendered in 3D with Three.js (r128, loaded
  from cdnjs). The rules, scoring and controls are identical; it adds a
  behind-the-bowler view, a tracking camera for shots, a side-on cut when
  the stumps are hit, and real shadows.
- Both files are written as page fragments (no `<html>`/`<body>` tags);
  browsers open them directly without trouble. There is no build step.

## Rules

Six players a side, five overs each. Wides cost two runs. A batter retires
not out at 50. The last batter standing bats on alone. Once per innings a
side may call a Blitz Over, where runs off the bat count double until a
wicket falls.
