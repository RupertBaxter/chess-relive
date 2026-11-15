# Chess Relive

Rewatch finished Lichess broadcast games in real time, with clocks reconstructed from the PGN `[%clk]` data.

- Browse/search Lichess broadcasts, pick a finished round and the games to watch
- Results hidden by default (reveal per board or globally)
- Play/pause, skip ±10s/1m/10m, jump to next move, speed 0.25×–10×
- Guess-the-move mode with score and instant feedback
- Auto / light / dark theme

## Run

Open `index.html` in a browser (double-click it). No server or build step is needed. Requires internet access (Lichess API, chess.js and piece images from jsDelivr).

Optionally, serve it locally instead:

```bash
python3 -m http.server 8765
```
