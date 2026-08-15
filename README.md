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

A small, personal archive of Minecraft modpacks I actually play. I export a pack, test it until it behaves, and keep the file here so I can grab it on any machine — no more hunting through old downloads or re-uploading the same files.

## The packs

| Pack | Version | Loader | Minecraft | File |
| :--- | :------ | :----- | :-------- | :--- |
| **NeoforgeRPG** | 1.0.0 | NeoForge | 1.21.1 | `modrinth/NeoforgeRPG.mrpack` |
| **Paleon** | 1.0.0 | Fabric | 1.21.11 | `modrinth/Paleon 1.0.0.mrpack` |

New packs land here as I make them. When a pack is reworked, the previous version stays around until the new one has proven itself.

## Layout

```
modpacks/
├── modrinth/               # .mrpack — Modrinth App, Prism, ATLauncher
│   ├── client/             # client-only packs
│   ├── server/             # server-only packs
│   └── *.mrpack            # full packs (client + server)
├── curseforge/             # .zip — CurseForge App
│   ├── client/
│   └── server/
└── README.md
```

Packs are grouped by source: each platform gets a folder, and a `client/` / `server/` subfolder appears where the split is worth making. Full packs sit at the top of their platform folder. The scheme is deliberately loose — a new source like FTB or Technic gets its own folder without disturbing anything else.

## Storage

The files are large, so `*.mrpack` and `*.zip` are stored with Git LFS instead of bloating the repository's regular history. Clones stay fast, and the repo stays lean.

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
