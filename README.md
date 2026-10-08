# monsterpocket-data

Game data for the MonsterPocket iOS app, published automatically.

| File | What |
|---|---|
| `manifest.json` | schema and data versions, source dates, size and SHA-256 of each file |
| `gamedata.json` | species, forms, moves and raid calculation inputs derived from the Pokémon GO Game Master |
| `pvp_rankings.json` | top PvP rankings per league with recommended movesets |

The app checks `manifest.json` once a day, downloads newer files, verifies every hash and falls back to the data bundled with the app if anything does not match.

Sources: Pokémon GO Game Master as published by [PokeMiners](https://github.com/PokeMiners/game_masters); PvP rankings from [PvPoke](https://github.com/pvpoke/pvpoke) (MIT). Pokémon and Pokémon GO are trademarks of their respective owners; this project is not affiliated with Niantic, Nintendo, The Pokémon Company or Game Freak.
