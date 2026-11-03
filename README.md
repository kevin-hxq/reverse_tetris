# Reverse Tetris: Beat the AI

**Play online:** [https://tetris.braingamehub.com](https://tetris.braingamehub.com)

Reverse Tetris is a browser game where you choose the pieces and the AI places them. Your goal is to stack the board until the AI can no longer make a move.

## How to Play

- Choose one of the seven tetrominoes. The AI automatically selects where and how to place it.
- You choose the order of the pieces. Each round includes one of each of the seven shapes; the set refreshes after all seven have been used.
- Cause the AI to top out to win.
- The board is 10 rows high.
- Use **Restart** to begin a new game. Use the language button to switch between English and Chinese; English is the default.

You can select pieces with the mouse or use the number keys **1–7**. The keys correspond to the pieces in the order shown: I, J, L, O, S, T, Z.

## Run Locally

The game is self-contained in `index.html` and requires no build step or dependencies. Open `index.html` in a modern web browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).
