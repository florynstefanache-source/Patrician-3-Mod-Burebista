[Español](README.es.md) · [Main page](README.md)

# Patrician 3 — Burebista Mod

**Reviewed release: v24 · Black-market ships delivered to Lübeck**  
**Mod author: Burebista**

Burebista expands Patrician III with its own tavern, maritime jobs, treasures, survivor rescues, a pirate black market, captured ships, reputation and a colony project. It also provides a customized visual presentation with maps, menus, backgrounds, ships, icons and nautical interface panels.

This release combines earlier improvements and fixes black-market ship delivery: purchased ships appear in **Lübeck**, damaged and ready for the player to order and pay for repairs at the shipyard.

## 1. Download and installation

[Download Burebista v24](https://github.com/florynstefanache-source/Patrician-3-Mod-Burebista/releases/tag/v24)

Full archive: `Burebista_v24_BARCOS_MERCADO_NEGRO_LUEBECK.zip`.

1. Close Patrician III and the Burebista launcher.
2. Extract the **entire ZIP** into a normal folder.
3. Run `INSTALAR_BUREBISTA.bat` and accept the administrator prompt.
4. The installer searches the usual Steam locations or lets you choose the game folder.
5. Wait for the installation success message.
6. Start the **Burebista** desktop shortcut or `INICIAR_BUREBISTA.bat`.

Do not run the installer from inside the ZIP.

The installer checks that the game is closed, copies the images, scripts, modules and launcher, and backs up existing files that it replaces into `BACKUP_BUREBISTA_date_time`. It avoids copying files onto themselves, registers the floating-chest texture if missing, verifies the required files and checks the v24 engine's SHA-256 hash. It also creates a desktop shortcut with the Burebista icon.

Extracting directly over the game and overwriting files before running the installer prevents it from recovering the original files already replaced. Extract into a separate folder first to preserve those originals.

**Executable compatibility:** the archive does not contain `Patrician3_1920x1080.exe`. The Burebista launcher contains a check requiring that executable. Although the BAT file has fallback paths, it launches `Burebista.exe` first when present. This edition is therefore not guaranteed to work with every original executable or resolution.

## 2. Burebista's tavern

A custom tavern is the hub for the new activities:

- Maritime jobs and assignments.
- Rumors about treasure, storms and shipwrecks.
- Collection of pending rewards.
- Influence and reputation information.
- Donations to improve reputation.
- Pirate black-market access.
- Captured-ship purchases.
- The Burebista colony project.
- A custom parchment background, decorative frame and character portrait.

The included guide describes access in **Lübeck**: select the warehouse until the **Warehouse** panel appears, then use the Burebista tavern entry. Detection uses the building panel rather than a fixed warehouse location.

The mod's menu and mission messages are in Spanish. This English documentation does not change the language of the game or mod.

## 3. Maritime jobs and missions

The tavern offers search, recovery and rescue assignments. The module contains these **15 named jobs**; original Spanish names are retained so players can identify them in the interface.

| In-game assignment | English meaning and objective |
| --- | --- |
| El navío perdido | The Lost Ship: find a merchant wreck and recover its cargo. |
| Contrabando real | Royal Contraband: find stolen barrels before the pirates return. |
| El último superviviente | The Last Survivor: locate a raft and rescue the sailor. |
| La herencia del capitán | The Captain's Inheritance: search a wreck for documents and loot. |
| Especias perdidas | Lost Spices: recover valuable cargo carried away by the current. |
| Mensajero en peligro | Messenger in Danger: rescue an emissary lost in the Baltic. |
| Barco fantasma | Ghost Ship: investigate remains sighted at night. |
| Las pieles del norte | Northern Furs: find lost bundles from a maritime caravan. |
| Capitán a la deriva | Captain Adrift: save an officer. |
| Tesoro de la Hansa | Hanseatic Treasure: recover the guild's chest from a shipwreck. |
| Cargamento sin dueño | Unclaimed Cargo: recover barrels floating away from trading routes. |
| Náufrago misterioso | Mysterious Castaway: rescue a man who claims to know a secret route. |
| Restos de la tormenta | After the Storm: find a ship sunk during the last storm. |
| Botín pirata | Pirate Loot: locate cargo abandoned after a naval battle. |
| Médico a la deriva | Doctor Adrift: rescue a surgeon. |

### Completing a tavern assignment

1. Open the tavern and select **Encargos** — jobs.
2. Read the assigned objective.
3. Send a ship to sea and sail until you locate it.
4. Recover the objective or rescue the survivor.
5. Return to the tavern when the completion notice appears.
6. Select **Recompensas** — rewards — to collect payment.

The messages distinguish active jobs, completed objectives and pending rewards. They also report failed reward delivery so the player can try again.

## 4. Chests, shipwrecks and survivors

- Floating treasure chests on the naval map, with their own graphic.
- Searching wreckage and recovering loot.
- Recovery of goods and valuable cargo.
- Rescue of sailors from rafts.
- Immediate rewards or a mission to transport a survivor to the next port.
- Maritime information that can reveal another chest's location.

For a sailor rescue, sail over the raft, wait for the reward or mission message, and, if transport is requested, enter a city and return to the naval map to complete delivery.

The included V1.1 mission guide lists rewards of **5,000–10,000 coins**, valuable goods, recovered cargo and information about new treasure. It describes a **10% chance** of an exceptional reward combining coins and a new treasure location. These figures come from that included historical guide; the internal v24 calculation has not been reconstructed.

## 5. Storms and navigation

The base retains the naval storm feature and storm-related events, together with the clock and expedition map mentioned in its release notes.

Tavern rumors include a strong storm approaching the Baltic and sightings of wrecks carrying valuable goods. The archive also supplies wave, iceberg, bird and marker graphics for the naval map.

## 6. Reputation, influence and tax discount

- An influence and reputation screen.
- Donations of **10,000**, **50,000** and **200,000 coins**.
- Display of current reputation and the active tax discount.
- Reputation stored in `mods/burebista_reputacion.dat`, separately from normal save files.
- Messages for insufficient money or failed reputation saving.
- A failed-save message stating that the donation has not been charged.

No readable conversion table linking donation amounts, reputation and tax-discount percentages was found in the package. Specific discount rates are therefore not claimed here.

## 7. Pirate black market

Players can buy stolen-goods lots and request another offer.

- Offers themed around convoy attacks, warehouse raids and intercepted Baltic ships.
- A displayed total price for each lot.
- Goods delivered to the player's ships.
- Cargo-space and money checks before purchase.
- An alert when none of the player's ships has enough space.
- Cancellation without charging when delivery fails, according to the module's messages.
- Corrected black-market product prices, documented in the stable-base notes.

The messages describe these goods as sold below market prices. A complete readable table of products, quantities and prices was not found, so no fixed price list is published here.

## 8. Captured ships

The tavern offers captured **Sniqqa, Craier, Cog and Holk** ships, using the module's own type names.

### v23 improvements retained in v24

- Purchased ships are created with damaged hulls.
- They are registered as the player's property.
- Owner, ship type, city, position and fleet linkage are validated before charging.
- Repairs do not start automatically: the player orders and pays for them at the shipyard.
- Maintenance no longer forces ordinary ships into automatic repairs.
- Rejected purchases report insufficient money, unavailable space, invalid fleet data or failed registration.

### Main v24 fix

- New purchases are delivered to **Lübeck**.
- Damaged **BOTIN** ships mistakenly sent to **Malmö** by older versions are automatically recovered in Lübeck when loading the save.
- Recovery does not charge for the purchase again.
- The v24 note states that this correction does not alter goods, the colony, factories or construction.

After loading, enter Lübeck and wait a few seconds before checking the harbor and shipyard.

## 9. Burebista colony and city

The colony project includes land searches, status information, a native contract and activation checks.

- Search for offers and sites using the game's native data.
- Land-availability diagnostics.
- Requesting and accepting the native contract.
- Instructions to advance game time and check progress.
- City activation and the **Burebista** name on the map and city windows.
- Access to the new city's native construction system.
- Messages for unavailable land, another active governor mission or an invalid contract.

The complete-base notes document the following construction options:

| Category | Documented options |
| --- | --- |
| Production | All factories unlocked in the base. |
| Urban infrastructure | Road and Well. |
| Administration | Town Hall. |
| Services | Tavern. |
| Military equipment | Weaponsmith and Armoury. |
| Harbor | Repair Dock. |
| Defense | Port bombard and Gate bombard. |
| Fortifications | Town wall with a valid construction record. |

**The v22 base explicitly excludes later instant-wall-construction experiments.** v24 retains that base, so instant walls are not advertised as an available feature.

Internal messages mention Windau and particular city identifiers during colony development. This does not establish multiple independent new maps or guarantee that every save has an available colony site.

## 10. Visual changes and included artwork

The ZIP contains **60 image files**, including the launcher icon, duplicate files and test variants. They were visually reviewed. This is an archive inventory, not a claim of 60 unique original designs or a comparison against a clean installation.

### Visual identity and menus

- A customized **Burebista** main menu with nautical scenery, parchment, coins and a decorative skull.
- A character-portrait launcher icon with a gold frame.
- A large custom tavern background.
- Gold-trimmed buttons and frames.
- Harbor and ship backgrounds for loading, credits, options, tutorial, save/load, end-game, settings and multiplayer screens.

Multiplayer background changes are visual; they do not imply new networking features.

### Maps and expeditions

- An illustrated naval map with a decorative frame and Burebista branding.
- Side panels with maps, nautical illustrations and compass/skull motifs.
- A Mediterranean expedition map.
- Included map masks and configurations.
- City, label and symbol positioning files.

Alternative maps in auxiliary folders should not be assumed to load simultaneously.

### Ships and fleets

- Sprite sheets for **Holk, Cog, Craier and Sniqqa**, showing different orientations.
- Sailing and anchored ship/convoy graphics.
- Naval information panels, indicators and a ship-deck image.
- Crew morale and hiring icons with character portraits.

These graphics alone do not establish changes to ship speed, cargo capacity, weapons or behavior.

### Buildings, events and objects

- Shipyard interior showing harbor work.
- Blacksmith interior with a craftsman and tools.
- Bathhouse interior.
- A weapons sprite sheet.
- Construction-menu icons.
- Maritime event and missing-goods icons.
- A barrel, bonus indicator and quill cursor.
- Floating-chest artwork and an additional chest variant.
- Wave, iceberg and bird sprite sheets.

### Artwork reference paths

| Content | Archive paths |
| --- | --- |
| Main menu | `images/Options/Hauptmenu.jpg` |
| Screen backgrounds | `images/Background/` |
| Naval map | `images/Vollansichtskarte.bmp` |
| Main panels | `images/HauptscreenA1280.bmp`, `HauptscreenE.bmp`, `HauptscreenE1280.bmp` |
| Side panels | `images/sidemenu/` |
| Automatic trade | `images/AutomatischerHandelBackground.bmp` |
| Fleet buttons | `images/b_schiffe_anker.tga`, `b_schiffe_see.tga`, `b_konvoi_anker.tga`, `b_konvoi_see.tga` |
| Ships | `images/Schiffe/page_mholk01.tga`, `page_mkogge01.tga`, `page_mkraier01.tga`, `page_mschnigge01.tga` |
| Construction and cursor | `images/page_baumenue.tga`, `menu01.tga`, `feder0003.tga` |
| Events | `images/Ereignisse/` |
| Expeditions | `images/Expedition/Mittelmeer.bmp` |
| Interiors and weapons | `images/Gebaeude_innen/` |
| Animations and floating chest | `images/Animationen_Seekarte/` |
| Tavern | `mods/taberna_burebista.bmp` |
| Alternative chest | `mods/cofre.bmp` |
| Launcher icon | `Burebista.ico` |

Names containing `-test`, `-buena` or `-modern` identify retained variants. Inclusion does not guarantee that the game loads them. The active texture configuration does reference the main menu, all four ship types, the Mediterranean map and several side panels, among other files.

## 11. Resolution, interface and fixes

- **1920 × 1080** map configuration in `scripts/accelMap.ini`.
- Included screen and texture scripts.
- City configurations in `StadtDaten.ini` and `cities_modified.txt`.
- Chat and focus fixes integrated into the main module, according to the stable-base notes.
- Executable checks before enabling certain construction and harbor-defense changes.

See the executable compatibility note in the installation section.

## 12. Required modules and saved data

Both modules are required and should remain together:

- `mods/cofres_navales.dll`: loads the current fixes and the stable module.
- `mods/cofres_navales_estable.dll`: contains the tavern, market, ships, missions and colony core for this edition.

Despite the second file retaining “estable” — stable — in its name, the installer verifies that its contents match **v24**.

Other important files are `Burebista.exe`, `Burebista.ico`, `mods/taberna_burebista.bmp`, the floating-chest texture and the `scripts` folder.

The modules contain paths for reputation, colony, market, ship and construction data/diagnostics under `mods`. Not every report exists before its associated function is used. Reputation is stored outside the normal save file, so retain the mod's data when moving an installation.

## 13. Documented development history

| Stage | Main contribution |
| --- | --- |
| V1.1 — Missions | Sailor rescues, delivery to port and random rewards. |
| Tavern beta | Jobs, rumors and rewards through Lübeck's warehouse panel. |
| Expanded stable base | Tavern, reputation, tax discount, black market, goods, ships, colony and chat/focus fixes. |
| v20 | Complete base with factories, services, defenses and valid wall construction. |
| v22 | Stable consolidation and ship registration/delivery improvements; excludes later instant-wall experiments. |
| v23 | Damaged ships with repairs ordered and paid for by the player. |
| v24 | Lübeck delivery and recovery of BOTIN ships incorrectly sent to Malmö. |

## 14. Review scope

This documentation was prepared by inspecting the v24 archive: its eight TXT guides, installers, scripts, 60 images and readable module strings. The binaries were not executed and no gameplay test was performed during this review.

Features are described from the included documentation and messages. Internal strings help identify menus, jobs and error handling, but do not replace a full code and runtime review. Unsupported figures or mechanics are not claimed.

Some historical guides conflict: one describes a pre-colony edition while later notes document colony activation. **v24, v23 and v22** notes take precedence here, retaining earlier features where those notes say they are preserved.

New naval statistics, AI changes, new commodities, expanded multiplayer and instant-wall construction are not presented as confirmed improvements.

Unofficial mod for **Patrician III**. Requires a compatible installation of the game.
