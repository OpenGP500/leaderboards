# OpenGP500 leaderboards (public data)

Read-only copy of the public leaderboard snapshots of OpenGP500, written by the leaderboard service once a day.
Contract: `opengp500/leaderboard` version 1. The game can read `v1/...` from here with the same paths as from the service.

- `v1/meta.json`, `v1/wr/`, `v1/challenges/`: the snapshots (JSON).
- `v1/ghosts/<sha256>.ogplap`: the ghosts of the published rows.
- `v1/images/<sha256>`: the PNG or JPEG image named by a challenge (`image` of its challenge.json; check its SHA-256).

This branch has no history: every dump is a single commit that replaces the previous one. Data deleted from the service
(for example a player who deletes their data) is no longer here after the next dump.
