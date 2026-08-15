```
                    ┌────────────────────────────────────┐
                    │                                    │
                    │   MALTE'S MODPACKS                 │
                    │   ──────────────────────────────   │
                    │   Personal Minecraft modpack archive│
                    │                                    │
                    └────────────────────────────────────┘
```

## Quickstart

```bash
git clone https://github.com/Malte-Dzierzon/modpacks.git
```

Clone the repo and import the pack you want into your launcher — `.mrpack` files work with the Modrinth App, Prism, ATLauncher, or any Modrinth‑compatible client; `.zip` packs go to the CurseForge launcher (Prism imports those too). The top‑level folders represent the platform; inside each you’ll find `client/` and `server/` sub‑folders when applicable. New platforms are added the same way.

## Was ist das?

Dieses Repository fasst die Modpack-Archive zusammen, die ich selbst zusammenstelle, teste und nutze. Sie sind nach Anbieter/Format sortiert und (falls relevant) danach, ob sie client‑ oder server‑seitig sind. Git LFS hält die großen Dateien außerhalb des normalen Git‑Objektverbunds, damit sich der Repository‑Umfang hält.

## Modpacks

| Pack | Version | Loader | Minecraft | Datei |
| :--- | :------ | :----- | :-------- | ----- |
| **NeoforgeRPG** | 1.0.0 | NeoForge | 1.21.1 | `modrinth/NeoforgeRPG.mrpack` |
| **Paleon** | 1.0.0 | Fabric | 1.21.11 | `modrinth/Paleon 1.0.0.mrpack` |

Weitere Packs landen hier, sobald ich sie mache, teste oder spiele. Wenn ein Pack überarbeitet wird, behalte ich die alte Version erst einmal bei.

## Ordnerstruktur

Derzeit sind die Packs nach Plattform (`modrinth/`, `curseforge/`, …) sortiert und innerhalb jeder Plattform optional nach `client/` und `server/`. Packs, die beide Seiten abdecken, landen direkt im Plattform‑Ordner. **Dieses Schema lässt sich jederzeit beliebig erweitern** – etwa um `ftb/`, `technic/` oder eigene Quellen. Jeder neue Ordner folgt derselben Konvention.

## Warum dieses Repository?

Ich spielte früher auf verschiedenen Maschinen und hatte jedes Mal die Pack‑Dateien neu besorgen müssen. Deshalb leben sie nun hier: clone, pack nehmen, weiterspielen.

Die großen Dateien werden von Git LFS verwaltet, damit sich der Repository‑Umfang im Rahmen hält.

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
