# Rain Ninja routing road packs

Offline routing road data for the Rain Ninja motorcycle ride planner (Android).
**The app downloads these packs automatically** when a ride start needs them, checks
every byte against SHA-256 values signed into the app, and installs them. You do not
need to download anything from here by hand.

| Release | Pack | Area | Data date |
|---|---|---|---|
| `roads-2026-10` | `routing-roads-britain-ireland-2026-10-19.zip` | Great Britain, Ireland, Isle of Man (domestic roads only) | 19 Oct 2026 |
| `roads-2026-10` | `routing-roads-central-europe-2026-10-20.zip` | Poland, Czech Republic, Denmark and eastern Germany (included sources) | 20 Oct 2026 |

Each ZIP contains a manifest, Valhalla routing tiles, road indexes and its licence.
`SHA256SUMS.txt` and the `*-source-manifest.json` files on each release describe the exact
sources. Packs are rebuilt from fresh data **every 3 months**.

Roads are a dated snapshot: some conditional, holiday and permit-only access rules are
not supported. Always follow current road signs. Travel times are estimates.

## Licence and attribution

The road data is derived from **© OpenStreetMap contributors**, available under the
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/),
and timezone data from timezone-boundary-builder (ODbL 1.0). Each pack and release
includes the full licence text (`*-road-data-LICENSE.txt`). Routing tiles were built
with Valhalla (MIT licence).

This repository contains data only — no application code.
