# Lore Chess

*A Lore Dungeon product.*

Chess against Stockfish, on a classic 2D board or in a 3D dungeon where captures turn into animated fights.
Includes puzzles, game review, clocks and saved games.

This repository holds the finished builds only. Download them from [Releases](../../releases).

## Install

### Mac (Apple Silicon and Intel)

```bash
brew install --cask imahungover/tap/lore-chess
```

If Homebrew says the tap is untrusted, run `brew trust --cask imahungover/tap/lore-chess` first.

Or download `LoreChess-mac.zip` from the latest release and move `LoreChess.app` to Applications.

The app is signed and notarized by Apple, so it opens without warnings.

Apple Silicon Macs need macOS 13 or later. Intel Macs need macOS 11 or later.

### Windows

```powershell
scoop bucket add imahungover https://github.com/ImAHungover/scoop-bucket
scoop install imahungover/lore-chess
```

Or download `LoreChess-windows.zip`, unzip it, and run `LoreChess.exe`. Windows may say it "protected your PC"
because the app is not signed: choose **More info**, then **Run anyway**.

### Linux (x86-64)

Download `LoreChess-linux.zip`, unzip it, and run `LoreChess.x86_64`.

## Licences

Every build includes `Licenses.txt` with the full terms. Lore Chess bundles:

| Part | Licence | Source |
|---|---|---|
| Stockfish 19, the chess engine, included unchanged as a separate program | GPL 3 | [official-stockfish/Stockfish, tag sf_19](https://github.com/official-stockfish/Stockfish/tree/sf_19) |
| Cburnett chess pieces | GPL 2 or later | [lichess-org/lila, public/piece/cburnett](https://github.com/lichess-org/lila/tree/master/public/piece/cburnett) |
| Merida chess pieces | GPL 2 or later | [lichess-org/lila, public/piece/merida](https://github.com/lichess-org/lila/tree/master/public/piece/merida) |
| Chessnut chess pieces | Apache 2.0 | [lichess-org/lila, public/piece/chessnut](https://github.com/lichess-org/lila/tree/master/public/piece/chessnut) |
| Godot Engine 4.7 | MIT | [godotengine.org/license](https://godotengine.org/license) |
| KayKit characters and dungeon, by Kay Lousberg | CC0 | [kaylousberg.com](https://www.kaylousberg.com) |
| Opening names (lichess-org/chess-openings) and puzzles (Lichess database) | CC0 | [lichess.org](https://lichess.org) |

The Lore Chess and Lore Dungeon names and logos belong to Lore Dungeon.
