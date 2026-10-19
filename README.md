# ChessForge • Beginner to Master Academy & Rapid AI Simulator

A complete, interactive chess training web application and Chess.com-style Rapid simulator designed for GitHub Pages.

## Features
- **7 Progressive Levels**:
  1. Board & Rules Fundamentals (Coordinates, Castling, En Passant, Promotion, Stalemate vs. Checkmate, Piece Values & Math)
  2. Opening Principles (Golden Trio, Tempo & Queen discipline, Italian Game, Caro-Kann, Punishing Scholar's Mate & Fried Liver)
  3. Tactical Patterns & Tricks (Forks, Pins, Skewers, Discovered Attacks, Removal of the Guard, Overloaded Defenders, Intermezzo, Smothered Mate, Windmill)
  4. Board Vision & Blunder Prevention (CCT: Checks, Captures, Threats routine, Loose Pieces LPDO, Attacker/Defender math, Prophylaxis)
  5. Positional & Strategic Concepts (King safety, Luft, Pawn structure weaknesses, Outposts, Rooks on the 7th rank)
  6. Essential Endgame Technique (K+Q, K+R box method, Ladder mate, Opposition rule, Rule of the Square, Tarrasch rule, Simplification)
  7. Playstyles & Rapid Mental Game (Tactical vs Positional styles, 10+0 and 15+10 time pacing, Tilt control, Post-game review protocol)
- **4-Phase Learning Loop**:
  1. Theory: Rich explanation & interactive demonstration board
  2. Guided Practice: Hands-on drill with move explanations and undo
  3. Lesson Test: Targeted scenario with trial-and-error feedback
  4. Level Exam: Multi-scenario test without category labels to test real board vision
- **Rapid Mock AI**:
  - 7 Calibrated AI difficulty tiers (~300 Elo Dumbass to ~2100+ Elo Extreme)
  - Time controls: 10+0 Rapid, 15+10 Rapid, 5+5 Blitz, Casual
  - Move notation log, captured piece display with real-time material differential (+3)
  - Toggleable real-time evaluation bar
  - In-game tactical coach and tips
- **Zero Dependencies**:
  - Pure vector SVG pieces and synthesized Web Audio effects (zero broken asset files)
  - Auto-saves progress to browser LocalStorage + JSON Export/Import for cross-device backup

## How to Deploy to GitHub Pages in 60 Seconds
1. Create a new repository on [GitHub](https://github.com).
2. Upload `index.html` to the repository root.
3. Go to **Settings** > **Pages**.
4. Under **Branch**, select `main` (or `master`) and folder `/ (root)`, then click **Save**.
5. Your chess academy will be live at `https://<your-username>.github.io/<repo-name>/`!
