# NOTICE - third-party components in Shrinefall

Shrinefall itself is proprietary; see [LICENSE](LICENSE). The components listed here are **not**
owned by RLD Games / Kaan Ipek and stay under their own licences, which the proprietary licence
explicitly carves out. The authoritative, per-pack inventory with the licence text of each pack is
`docs/LICENCES.md` in the source tree; this file is the copy that travels with the public build
pipeline repository.

Attribution obligations, in one line: **CC0 requires none**, **the SIL OFL requires that its licence
text ships with the fonts**, and the free packs below ask only that the art not be resold or claimed
as one's own. Credits are shown in the game's settings screen; nothing here requires attribution, it
is given anyway.

## 1. Pixel art, tilesets, FX, UI

| Component | Author | Licence | Used for |
|---|---|---|---|
| Ninja Adventure Asset Pack | Pixel-boy & AAA (pixel-boy.itch.io) | CC0 1.0 | actors, bosses, tilesets, items, FX, UI theme, music, sounds, NormalFont |
| Pixel Crawler - Free Pack 2.11 | Anokolisa | free for games, no resale of the art, credit appreciated | environment props |
| 0x72 Dungeon Tileset II 1.7 | 0x72 | CC0 1.0 | dungeon props |
| Kyrise's Free 16x16 RPG Icon Pack 1.3 | Kyrise | free | item icons |
| RPG Arsenal 1.1 | LimeZu | free ("anything but claiming the art as yours") | item icons |
| Pixel Art Icon Pack - RPG | library copy | free pack | item icons |
| Kenney Mobile Controls 1.0 | Kenney | CC0 1.0 | joystick and buttons |

## 2. Audio

| Component | Author | Licence | Used for |
|---|---|---|---|
| Ninja Adventure Asset Pack (music + SFX) | Pixel-boy & AAA | CC0 1.0 | zone music, hit/pickup sounds |
| Kenney RPG Audio | Kenney | CC0 1.0 | UI and pickup sounds |
| 28 High Quality 16-bit RPG Music | HydroGene | free, credit not mandatory | boss themes |

## 3. Fonts - SIL Open Font License 1.1

| Font | Author | Licence |
|---|---|---|
| Barlow | Jeremy Tribby | SIL OFL 1.1 (body font) |
| NormalFont (Ninja Adventure) | Pixel-boy & AAA | CC0 1.0 |
| Liberation Sans (TextMesh Pro default) | Red Hat / Google | SIL OFL 1.1 |

Under the OFL these fonts may be bundled and redistributed inside the game provided the licence text
travels with them, they are not sold on their own, and no modified version reuses the reserved names.

## 4. Engine and packages

Unity 6000.4.8f1 and the packages in `Packages/manifest.json` - Universal Render Pipeline, 2D
Pixel Perfect, Netcode for GameObjects 2.5.1, Unity Transport, Relay 1.1.1, Authentication 3.7.0,
Services Core, Burst, Collections, Mathematics, TextMesh Pro / uGUI - are used under Unity's own
terms (the Unity Companion License, the Unity Package Distribution License or the Unity Terms of
Service, per package). The Unity Gaming Services "wire" and transport packages vendor MIT and
Apache-2.0 components (websocket-sharp, mbedTLS via UnityTLS); their notices ship inside the
respective package folders and are reproduced by Unity's own licence text.

MCP for Unity (`com.coplaydev.unity-mcp`, MIT) is a development-time editor bridge and is removed
from the manifest before any store build; it is not part of a shipped Shrinefall binary.

## 5. Not in this repository

The public pipeline repository holds an encrypted archive of a generated Xcode project and a
workflow. It contains none of the components above in readable form and grants no licence to any
of them; each component's licence applies to the component as obtained from its author.
