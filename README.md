# Speel als een Romein — Roman Board Game

An interactive browser implementation of an ancient Roman board game, based on a ruleset published by **Universiteit Maastricht** (Faculty of Science and Engineering) in collaboration with Universiteit Leiden, Het Romeins Museum, and Restauratieatelier Restaura.

Play it here: **[jhgcreugers1.github.io/roman-game](https://jhgcreugers1.github.io/roman-game)**

---

## About the Game

This is a two-player strategy game reconstructed from a Roman stone game board. One player is the **Jager** (hunter, 4 pawns) and the other is the **Prooi** (prey, 2 pawns). The hunter moves first. The goal is to trap both prey pawns in as few moves as possible.

The board is a rectangle with a horizontal divider and chamfered corners, based on markings found on an actual Roman stone artifact.

### Rules

- Players alternate moving one pawn per turn along a line to an adjacent intersection
- You may not jump over another pawn
- Two pawns may not occupy the same spot
- A pawn is trapped when it has no legal moves
- The game ends when both prey pawns are trapped
- Then roles are swapped — the hunter who traps the prey in fewer moves wins
- A tie means you play again

---

## Credits & Attribution

The game rules and board design are based on materials published by:

- **Universiteit Maastricht**, Faculty of Science and Engineering
- **Universiteit Leiden**
- **Het Romeins Museum**
- **Restauratieatelier Restaura**

The original ruleset document: *"Speel als een Romein"* (2026).
The game was researched and formalized using [Ludii](https://ludii.games/), a general game system developed at Maastricht University.

The ancient game itself is in the public domain — it originates from Roman antiquity. This implementation is an independent fan/educational reimplementation. No original text, images, or Ludii code from the publishers was reproduced.

If you are one of the rights holders and have any concerns, please open an issue or get in touch.

---

## How to Run Locally

No build step needed. Just open the file in a browser:

```bash
git clone https://github.com/yourusername/roman-game.git
cd roman-game
open index.html   # or double-click the file
```

---

## License

The **code** in this repository is released under the [MIT License](LICENSE).  
This does not cover the game rules or board design, which belong to their respective creators (see Credits above).
