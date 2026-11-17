# Configuration

Trailmark reads its settings from a local `.env` file. Copy `.env.example` to `.env` and fill in the values below.

| Variable | Current Value | Purpose |
|---|---|---|
| `MAPTILES_SYNC_ID` | `k7Qx****L4tD` (see your `.env`) | Identifier used to sync tile cache with the service |
| `MAPTILES_STYLE` | `outdoors-v2` | Base map style |

`MAPTILES_SYNC_ID` is a per-developer credential, so the real value is kept in your local `.env` file (which is gitignored) rather than committed here.
