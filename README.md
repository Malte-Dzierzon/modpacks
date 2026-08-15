```
┌──────────────────────────────────────────────┐
│                                              │
│   MALTE'S MODPACKS                           │
│   ────────────────────────────────           │
│   Personal Minecraft modpack collection      │
│                                              │
└──────────────────────────────────────────────┘
```

## Quickstart

```bash
git clone https://github.com/Malte-Dzierzon/modpacks.git
```

Import the pack you want and go. `.mrpack` files install in the Modrinth App, Prism Launcher, or ATLauncher; `.zip` packs are CurseForge exports for the CurseForge App (Prism imports those as well). If a pack needs a specific loader, the table below says which.

## What this is

A small, personal archive of Minecraft modpacks I actually play. I export a pack, test it until it behaves, and keep the file here so I can grab it on any machine — no more hunting through old downloads or re-uploading the same files. Each modpack lives in its own folder, split into a full client version and a lean server version, so I can hand out the right one without thinking.

## The packs

| Pack | Version | Loader | Minecraft | File |
| :--- | :------ | :----- | :-------- | :--- |
| **NeoforgeRPG** | 1.0.0 | NeoForge | 1.21.1 | `NeoforgeRPG/client/NeoforgeRPG.mrpack` |
| **Paleon** | 1.0.0 | Fabric | 1.21.11 | `Paleon/client/Paleon 1.0.0.mrpack` |

New packs land here as I make them. When a pack is reworked, the previous version stays around until the new one has proven itself.

## Layout

```
modpacks/
├── NeoforgeRPG/
│   ├── client/               # full pack for players
│   └── server/               # stripped server version
└── Paleon/
    ├── client/
    └── server/
```

One folder per modpack. The `client/` folder holds the pack as players run it — mods, resource packs, shaders, all of it. The `server/` folder holds the version that actually runs on a server: no Sodium, no cosmetic or client-only mods, just what the server needs. Each side can ship as a Modrinth (`.mrpack`) or CurseForge (`.zip`) export — the extension says which is which.

The scheme is open by design. New packs, extra formats, or additional subfolders extend this layout without breaking anything that's already here.

```
                ▄ ▄ ▄
              ▄ █ █ █ ▄
            ▄ █ █ █ █ █ ▄
          ▄ ▄ ▄ ▄ ▄ ▄ ▄ ▄ ▄
          █ █ ▄ ▄ ▄ ▄ █ █
          █ █ ▄ ▄ ▄ ▄ █ █
          █ ▄ █ █ █ █ ▄ █
          ▄ █ █ ▄ ▄ █ █ ▄
            ▄ █ █ █ █ ▄
              ▄ ▄ ▄ ▄
```
