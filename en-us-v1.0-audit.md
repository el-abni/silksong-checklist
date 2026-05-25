# EN-US 1.0 Audit

## Summary

* Input version: PT-BR 1.0 (`index.html`)
* Output version: EN-US 1.0
* Root PT-BR preserved: Yes. The root app keeps the PT-BR data and storage key; only a small language link was added.
* EN-US path: `en/index.html`
* Total items: 124
* Total percentage: 100%
* IDs preserved: Yes. Item IDs and section IDs match the PT-BR version.
* localStorage separated: Yes. EN-US uses `silksong-100-checklist-abni-enus-v1`; PT-BR keeps `silksong-100-checklist-abni-ptbr-v1`.
* Layout preserved: Yes. The EN-US version is the same single-file app and keeps the approved visual structure.

## Sources consulted

| Source | URL | Type | Used for |
| ------ | --- | ---- | -------- |
| Steam Community achievements | https://steamcommunity.com/stats/1030300/achievements/ | Official platform listing | Achievement names and descriptions, especially Completion, Speed Completion, Steel Soul, and Steel Heart |
| Hollow Knight Wiki - Completion (Silksong) | https://hollowknight.wiki/w/Completion_%28Silksong%29 | Community wiki | Completion categories, item names, percentage structure, and achievement cross-checks |
| Hollow Knight Wiki - Tools | https://hollowknight.wiki/w/Tools | Community wiki | Tool names, colors, categories, vendors, prices, and upgraded variants |
| Hollow Knight Wiki - Mask Shard (Silksong) | https://hollowknight.wiki/w/Mask_Shard_%28Silksong%29 | Community wiki | Mask Shard sources, requirements, wishes, vendors, and bosses |
| Hollow Knight Wiki - Spool Fragment | https://hollowknight.wiki/w/Spool_Fragment | Community wiki | Spool Fragment sources, requirements, wishes, and vendors |
| Hollow Knight Wiki - Skills and Abilities (Silksong) | https://hollowknight.wiki/w/Skills_and_Abilities_%28Silksong%29 | Community wiki | Ancestral Arts, Silk Skills, Needle Strike, Sylphsong, and Everbloom names |
| Hollow Knight Wiki - Pale Oil | https://hollowknight.wiki/w/Pale_Oil | Community wiki | Needle upgrade names, Pinmaster Plinney, Pale Oil sources, and Rosary costs |
| Hollow Knight Wiki - Silk Heart | https://hollowknight.wiki/w/Silk_Heart | Community wiki | Silk Heart sources, memories, Bell Beast, The Unravelled, Lace, and The Cradle |
| Hollow Knight Wiki - Crests | https://hollowknight.wiki/w/Crests | Community wiki | Crest names and completion membership |
| Hollow Knight Wiki - Architect Crest | https://hollowknight.wiki/w/Architect_Crest | Community wiki | Architect Crest, Architect Key, Twelfth Architect, 25 Tools requirement, and price |
| Hollow Knight Wiki - Needle Strike | https://hollowknight.wiki/w/Needle_Strike | Community wiki | Focus Attack terminology resolved as Needle Strike |
| Hollow Knight Wiki - Sylphsong | https://hollowknight.wiki/w/Sylphsong | Community wiki | Sylphsong name, Eva source, and 32 Crest slots requirement |
| Hollow Knight Wiki - Everbloom | https://hollowknight.wiki/w/Everbloom | Community wiki | Everbloom name, Red Memory, and Moss Grotto source |

## Terminology changes

| PT-BR term | EN-US term | Source/Reason |
| ---------- | ---------- | ------------- |
| Tessela | Lace | Wiki character and Silk Heart pages |
| Corbos | Craws / Craw Lake | Skills and area references |
| Pulgopolis | Fleatopia | Tool Pouch and Flea Caravan references |
| Rosarios | Rosaries | Wiki item and vendor wording |
| Oleo Palido | Pale Oil | Pale Oil page |
| Campanula | Bellhart | Wiki area and Pale Oil pages |
| A Medula | The Marrow | Wiki area references |
| Vale dos Ossos | Bone Bottom | Wiki area references |
| Docas Profundas | Deep Docks | Wiki area references |
| Pantano Cinzento | Greymoor | Wiki area references |
| Cidadela | Citadel | Wiki area references |
| O Berco | The Cradle | Silk Heart and skill pages |
| Ala Branca | Whiteward | Wiki page spelling uses Whiteward |
| Saloes Harmonicos | Choral Chambers | Pale Oil page |
| Claustroforjas | Underworks | Crest and tool pages |
| Monte Plumidio | Mount Fay | Mask Shard and requirement references |
| Manto do Errante | Drifter's Cloak | Wiki ability/item references |
| Manto de Plumidio | Faydown Cloak | Wiki ability/item references |
| Garra de Seda | Clawline | Skills and Abilities page |
| Garra Aderente | Cling Grip | Skills and Abilities page |
| Impulso de Seda | Silk Soar | Skills and Abilities page |
| Passo Veloz | Swift Step | Skills and Abilities page |
| Agulino | Needolin | Skills and Abilities page |
| Melodia Triplice | Threefold Melody | Silk Heart page |
| Coracoes de Seda | Silk Hearts | Completion and Silk Heart pages |
| Fragmentos de Mascara | Mask Shards | Completion and Mask Shard pages |
| Fragmentos de Carretel | Spool Fragments | Completion and Spool Fragment pages |
| Brasoes | Crests | Completion and Crests pages |
| Ferramentas | Tools | Completion and Tools pages |
| Conjunto de Fabricacao | Crafting Kit | Completion and Tools pages |
| Bolsa de Ferramentas | Tool Pouch | Completion and Tool Pouch references |
| Ataque de Foco | Needle Strike | Needle Strike page |
| Silfonia | Sylphsong | Sylphsong page |
| Flor-da-Eternidade | Everbloom | Everbloom page |
| Coracao de Aco | Steel Heart | Steam achievements |
| Agulha Afiada | Sharpened Needle | Pale Oil page |
| Agulha Reluzente | Shining Needle | Pale Oil page |
| Agulha de Aco Favonio | Hivesteel Needle | Pale Oil page |
| Agulha de Aco Palido | Pale Steel Needle | Pale Oil page |

## UI changes

* Search placeholder translated to `Search item, location, requirement, act...`.
* Status filters translated to `All`, `Completed`, and `Pending`.
* Act filters translated to `All Acts`, `Act 1`, `Act 2`, and `Act 3`.
* Tool-color filters translated to `All Colors`, `Red Tools`, `Blue Tools`, and `Yellow Tools`.
* Mode button translated between `Compact Mode` and `Detailed Mode`.
* Command buttons translated to `Export`, `Import`, `Reset`, `Mark Visible`, and `Unmark Visible`.
* Side panels translated to `Category Summary`, `Completion Achievements`, and `Notes`.
* Legal panels translated to `Credits and Notices`, `Creators`, and `Project License`.
* Import, export, reset, confirmation, and invalid-file messages were translated.
* Export filename changed to `silksong-checklist-en-us.json`.

## Section changes

### Needle

Converted all 4 Needle upgrades to official EN-US names and natural acquisition text. Pinmaster Plinney, Bellhart, Pale Oil, Rosaries, and Pale Oil source notes were restored to English.

### Ancestral Arts

Converted all 5 abilities to official EN-US names: Clawline, Cling Grip, Needolin, Silk Soar, and Swift Step. Clawline keeps Hornet fallback behavior and does not get a Trobbio character icon.

### Silk Skills

Converted all 6 Silk Skills to official EN-US names: Silkspear, Thread Storm, Cross Stitch, Sharpdart, Rune Rage, and Pale Nails. Phantom and relevant locations were restored to English.

### Mask Shards

Converted all 20 Mask Shards to EN-US item names and route text. Vendors, wishes, prices, bosses, and requirements were rewritten in short player-facing English.

### Spool Fragments

Converted all 18 Spool Fragments to EN-US item names and route text. Vendor prices, wish rewards, and movement requirements were preserved.

### Silk Hearts

Converted all 3 Silk Hearts. Bell Beast, The Unravelled, Lace, Threefold Melody, Whiteward, and The Cradle were restored to English.

### Crests

Converted all 6 Crests. Architect Crest, Architect Key, Twelfth Architect, the 25 Tools requirement, chapel names, and the 110 Rosaries price were restored to English.

### Crafting Kit

Converted all 4 Crafting Kit upgrades. Vendors, prices, and requirements were rewritten in English while preserving IDs, acts, and percentages.

### Tool Pouch

Converted all 4 Tool Pouch upgrades. Mort, Loddie, Nuu, Fleamaster Mooshka, Fleatopia, 22 Fleas, and Pale Lake were restored to English.

### Miscellaneous

Converted Focus Attack to Needle Strike, Silphony to Sylphsong, and Everlasting Flower / Everbloom wording to Everbloom. Farsight remains a note-only concept because it does not add 1%.

### Tools

Converted all 51 Tools to EN-US names, with color categories, vendors, prices, materials, wishes, NPCs, requirements, acts, and upgraded variants kept in the same data model.

### Achievements

Converted achievement cards to Steam EN-US names: Completion, Speed Completion, and Steel Heart.

### Notes

Rewrote the notes in natural EN-US, kept to 6 short player-facing notes, and removed audit wording.

### Credits

Translated credits, Team Cherry notice, creator labels, and MIT license explanation. Abni and Meykozi☆ credits were preserved.

## Uncertain terms

| Item/Term | Chosen EN-US text | Uncertainty | Sources checked |
| --------- | ----------------- | ----------- | --------------- |
| Whiteward | Whiteward | The user prompt suggested `White Ward`, but the checked wiki pages use the one-word spelling. | Silk Heart, Mask Shard, Spool Fragment, and area references |
| Conchcutter source detail | Defeat Raging Conchfly, then take Conchcutter in Coral Tower | The tool name and Coral Tower source were confirmed; the boss wording was retained from the PT-BR route context and guide cross-checks. | Tools page and search cross-checks |
| Tool Pouch 1 location | Pilgrim's Rest | Mort and the 220 Rosaries price were confirmed; the exact display wording for the shop location was less directly exposed in the consulted pages. | Tool Pouch references and completion cross-checks |
| Crafting Kit 2 prerequisite | Complete SAVE: The Threadspun Town to unlock Creige's sequence | Creige, Crawbug Clearing, and Halfway Home were confirmed; the prerequisite wording follows the PT-BR structure. | Crafting Kit references and completion cross-checks |
| Witch Crest quest wording | Twisted Bud with Greyroot; complete Rite of Rebirth, then Infestation Operation | Crest name and membership were confirmed; the quest-chain wording follows source cross-checks and the PT-BR item structure. | Crests page and wish/quest cross-checks |

## Validation

* `/index.html` still exists and remains PT-BR: Confirmed.
* `/en/index.html` exists: Confirmed.
* `DATA.version = "EN-US 1.0"` in EN-US: Confirmed.
* Total percentage = 100: Confirmed.
* Total items = 124: Confirmed.
* Unique item IDs = 124: Confirmed.
* Section IDs preserved: Confirmed.
* Percentages preserved: Confirmed.
* Acts preserved: Confirmed.
* Color categories preserved: Confirmed.
* `checkCharacter` values preserved: Confirmed.
* Clawline does not use `checkCharacter: "trobbio"`: Confirmed.
* Import/export/reset controls preserved: Confirmed.
* EN-US localStorage separated from PT-BR: Confirmed.
* Filters preserved: Confirmed.
* Search bar preserved: Confirmed.
* Compact/detailed mode preserved: Confirmed.
* HTML script parses without syntax error: Confirmed.
* Creator block preserved: Confirmed.
* Team Cherry notice preserved and translated: Confirmed.
* Project license block preserved and translated: Confirmed.
* No obvious PT-BR terms remain in visible EN-US text or EN-US data strings: Confirmed. Base64 image data was excluded from this check.
* No audit wording remains in visible EN-US text or item data: Confirmed. Internal enum values such as `pending` remain as app state values only.
* `/en/` works as a static page path: Confirmed by local HTTP fetch.

