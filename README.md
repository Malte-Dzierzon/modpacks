```
                    ┌──────────────────────────────────────┐
                    │                                      │
                    │   MALTE'S MODPACKS                   │
                    │   ─────────────────────────────      │
                    │   Personal Minecraft modpack archive │
                    │                                      │
                    └──────────────────────────────────────┘
```

## Quickstart

```bash
git clone https://github.com/Malte-Dzierzon/modpacks.git
```

Grab the pack you want and import it — `.mrpack` files belong to the Modrinth App, Prism Launcher, ATLauncher, or any launcher that speaks Modrinth; `.zip` packs go into the CurseForge launcher (Prism imports those too). Each platform folder in this repo says which launcher it's for, so you never have to guess.

## Modpacks

| Pack | Version | Loader | Minecraft | File |
| :--- | :------ | :----- | :-------- | :--- |
| **NeoforgeRPG** | 1.0.0 | NeoForge | 1.21.1 | `modrinth/NeoforgeRPG.mrpack` |
| **Paleon** | 1.0.0 | Fabric | 1.21.11 | `modrinth/Paleon 1.0.0.mrpack` |

More packs will keep landing here as I make, test, and play them. If one of my packs goes through a rewrite, I keep the old version around until the new one has proven itself.

## Layout

```
modpacks/
├── modrinth/                 # .mrpack — Modrinth App, Prism, ATLauncher
│   ├── client/               #   client-only packs
│   ├── server/               #   server-only packs
│   ├── NeoforgeRPG.mrpack
│   └── Paleon 1.0.0.mrpack
├── curseforge/               # .zip — CurseForge App
│   ├── client/
│   └── server/
└── README.md
```

A pack that works on both sides (most do) sits directly in the platform folder. Only packs that are deliberately client-only or server-only go one level down. Other sources get their own folder when the need comes up.

## Why this exists

I export packs, I play them on different machines, and I got tired of re-uploading the files. So they live here instead. Clone anywhere, take what you need, keep playing.

The large files are handled by Git LFS, so the repository itself stays lean.

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

---

<p align="center">
  <sub>Minecraft · Modrinth · CurseForge · Git LFS</sub>
</p>
