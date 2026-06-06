# ♟ GRANDMASTER — 3D Chess

A premium AAA-level 3D chess game built with Three.js.

## How to Run

### Option 1 — Open directly (recommended for Chrome/Firefox)
Just double-click `index.html` — it loads from CDN, no server needed.

### Option 2 — Local server (if CORS issues)
```bash
# Python 3
python3 -m http.server 8080
# Then open: http://localhost:8080
```

### Option 3 — VS Code Live Server
Install the "Live Server" extension, right-click `index.html` → Open with Live Server.

---

## Controls

| Action | Control |
|--------|---------|
| Select piece | Left click |
| Move piece | Click destination |
| Rotate camera | Right-click drag |
| Zoom | Scroll wheel |
| Touch rotate | 1-finger drag |
| Touch zoom | Pinch |

## Features

- ✅ Full chess rules (all pieces, castling, en passant, promotion)
- ✅ Check, checkmate, stalemate detection
- ✅ 3D board with Three.js + realistic lighting & shadows
- ✅ Smooth piece movement animations with arc tweening
- ✅ Check glow (red pulse on king square)
- ✅ Move hints (dots for empty, rings for captures)
- ✅ Last move trail highlight
- ✅ Move history sidebar with algebraic notation
- ✅ Undo/Redo system
- ✅ Flip board
- ✅ Captured pieces panel with material score
- ✅ AI opponent (4 difficulty levels, Minimax + Alpha-Beta)
- ✅ Cinematic camera on checkmate
- ✅ 3 board themes: Royal (blue/gold), Neon (teal/dark), Wood
- ✅ Ambient particle effects
- ✅ Sound effects (move, capture, check, checkmate, castle)
- ✅ Pawn promotion dialog
- ✅ Glassmorphism UI panels
- ✅ Touch / mobile support

## Tech Stack
- Three.js r128 (3D rendering)
- Tween.js 18.6 (smooth animations)
- Pure JavaScript chess engine (no library dependency)
- Minimax with Alpha-Beta pruning for AI
