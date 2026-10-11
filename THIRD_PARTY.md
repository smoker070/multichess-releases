# Third-party software and content

| Component | Use | Licence | Source |
|---|---|---|---|
| **Stockfish 19** | chess engine, bundled in the installers | GPL-3.0 | https://github.com/official-stockfish/Stockfish (the installers carry the unmodified official binary) |
| **python-chess** | rules, PGN, engine protocol (`chess.svg` pieces at build time) | GPL-3.0 | https://github.com/niklasf/python-chess |
| **PyWebView** | native window | BSD-3-Clause | https://github.com/r0x0r/pywebview |
| **PyInstaller** | packaging (build time only) | GPL-2.0 with the bootloader exception | https://pyinstaller.org |
| **Cburnett chess pieces** | built-in piece set | CC BY-SA 3.0 / GPL-2.0+ | https://commons.wikimedia.org/wiki/Category:SVG_chess_pieces |
| **Lichess chess-openings** | opening names (`openings/*.tsv`) | CC0 | https://github.com/lichess-org/chess-openings |
| **Lichess masters explorer** | optional deeper "book" check (network, off by default) | Lichess API terms | https://lichess.org/api |
| **Background photographs** | `backgrounds/*.jpg` | CC BY / CC BY-SA, authors in `backgrounds/CREDITS.md` | Wikimedia Commons |
| **Spatial bishop fix** | `pieces_overrides/` (our edit of the Lichess "spatial" set) | GPL-3.0 (set licence) | https://github.com/lichess-org/lila |

## Piece sets (`pieces/`)

Ten extra piece sets are bundled; they come from the Lichess "lila" repository and each keeps its own licence
(full list in `pieces/COPYING.md`):

| Set | Author | Licence |
|---|---|---|
| merida | Armando Hernandez Marroquin | GPL-2.0+ |
| chessnut | Alexis Luengas | Apache-2.0 |
| spatial, celtic | Maurizio Monge | MIT |
| mpchess | Maxime Chupin | GPL-3.0+ |
| kosal | Kosal Sen | CC BY 4.0 |
| caliente (avi), maestro (sadsnake1), anarcandy (caderek) | see `pieces/COPYING.md` | **CC BY-NC-SA 4.0 (non-commercial)** |
| alpha | Eric Bentzen | **free for personal non-commercial use** |

The last two rows mean Multichess may only be distributed free of charge as long as these sets are included.
Remove `caliente`, `maestro`, `anarcandy` and `alpha` from `pieces/` before any commercial use.

Multichess is not affiliated with chess.com, Lichess or the Stockfish team. chess.com data is read through its public
Published-Data API; no chess.com artwork is used.
