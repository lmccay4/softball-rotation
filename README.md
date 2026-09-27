# 🥎 Softball Rotation Builder

A single-page web app for building a softball depth chart and defensive rotation
(10 fielders, 4 outfielders), with the goal that no player sits two innings in a row.

**Live app:** https://lmccay4.github.io/softball-rotation/

## Features

- **Roster:** mark who's at tonight's game; "Never sits" for anyone who plays every inning.
- **Depth chart:** rank players at each of the 10 positions.
- **Rotation generator:** fills every inning so nobody sits back-to-back, sitting time is even,
  and players land where they're ranked highest.
- **Outfield platoons (optional):** RF → RCF → sit and LCF → LF → sit. Adapts to how many
  outfielders are there.
- **Auto-fill:** set up inning 1 by hand and the rest follows.
- **Editable grid:** change any player/position/inning right in the table.
- **Open-spot helper:** shows who could fill an empty position in the selected inning.
- **Batting order:** sort the grid by it and print a one-page dugout card.

## Running it

It's a single `index.html` with no build step or dependencies. Open it in a browser, or use the live link.
Data is saved in your browser (localStorage). Use **Export backup / Import backup** on the Roster
tab to move it between devices.
