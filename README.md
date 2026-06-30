# fabric-scoop-central

A [scoop](https://scoop.sh) bucket for the V-Sekai multiplayer fabric Windows apps.

## Use

```powershell
scoop bucket add fabric-scoop-central https://github.com/v-sekai-multiplayer-fabric/fabric-scoop-central
scoop install loop-slice
```

That installs the loot-action demo and puts three commands on your `PATH`:

- `loop-slice-demo` — run the all-in-one demo (server + bots + your client + observability)
- `loop-slice-server` — host the server for other machines (prints this PC's LAN address)
- `loop-slice-client` — connect to a server's address and play

It also adds a **V-Sekai Loop-Slice Demo** Start-menu shortcut. Update with
`scoop update loop-slice`; remove with `scoop uninstall loop-slice`.

## Manifests

- [`loop-slice`](bucket/loop-slice.json) — the
  [godot-loop-slice](https://github.com/v-sekai-multiplayer-fabric/godot-loop-slice) native
  Windows demo, from its release zip.
