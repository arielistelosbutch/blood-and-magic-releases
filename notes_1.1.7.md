## CZ
### Novinky ve verzi 1.1.7
- **Opraveno: golemové zaseknutí při proměně.** Golem, kterému během proměny (kukly) přišel rozkaz k pohybu, např. při rozkazu celé vybrané skupině, zůstal napůl proměněný na jednom políčku, pořád se přepínal mezi kuklou a chůzí a nešel ovládat, rozpustit ani zničit. Probíhající proměnu teď žádný rozkaz nepřeruší a golemové, kteří se takhle zasekli ve starších uložených pozicích, se při dalším rozkazu sami opraví.
- Zablokovaný golem, který čeká, až se mu uvolní cesta, se už nepřeměňuje do obelisku a zpět.

### Novinky ve verzi 1.1.6
- **Turbo mód pro skirmish (volitelný)**: v nastavení skirmishe přibyla volba PRAVIDLA – PŮVODNÍ / TURBO (3× mana a zkušenosti, +2 golemové) / BLESK (6×, +4 golemové) / VLASTNÍ (hodnoty turbo_* v bamport.ini). Platí pro obě strany stejně. Kampaň a síťová hra mají vždy původní pravidla, výchozí je PŮVODNÍ.
- **Opraveno: Basal Golem uvízlý na portálu** se pořád proměňoval do obelisku a zpět a nešel ovládat ani rozpustit. Stávalo se to při automatickém vyvolávání, když byl portál obklopený meditujícími golemy. Hra teď golema obklíčeného ze všech stran nechá v klidu. Automatická výroba v budovách už také nevybírá golemy, kteří se nemají kam pohnout.

### Novinky ve verzi 1.1.5
- **Opraveno: pád hry při dvojkliku na jednotku** (výběr všech jednotek stejného typu), pokud byla mezi nimi jednotka, kterou hra zrovna ovládá sama.

### Novinky ve verzi 1.1.4
- **Chytřejší nepřítel (AI)**: golemové už nechodí sami útočit na nepřátelskou základnu ani se nezapojují do protiútoků, nečekají zbytečně u portálu a u budovy počkají na manu, místo aby proměnu vzdali – AI tak vyrobí víc jednotek a drží větší armádu. Obránci nepřebíhají mezi budovami a brání tu, která je napadená. Stavební party nestaví v nepřátelské základně. Jednotky na strategických bodech už nechodí do rohu mapy a bod chvíli drží.
- **Lepší hledání cest**: jednotky se už nevydávají slepými objížďkami, nezastavují se po ústupu o políčko dřív a jednotka v cestě se odstrčí, místo aby mohla zaniknout.
- **Automatická výroba v budovách**: vyber budovu (např. kasárna) a klikni **pravým tlačítkem na tlačítko proměny** – každé kliknutí přepne na další vyzkoumanou jednotku, nakonec se výroba vypne. Nečinní golemové pak sami dojdou k budově a promění se. Vždy zůstanou aspoň 4 golemové. Budova má zlatý rámeček a drahokam.
- **Klávesa Q** zapne / vypne automatické vyvolávání golemů.
- **Shift + číslo** přidá vybrané jednotky do už vytvořené skupiny (Ctrl + číslo).
- **Opraveno**: po načtení uložené pozice z hlavního menu nešla měnit rychlost hry.
- Nové ovládání je v nápovědě (F1).
- Uložené pozice ze starší verze nejdou načíst uprostřed mise; kampaň ale pokračuje od začátku aktuální mise (Hra jednoho hráče → Pokračovat). Doporučujeme si saves před aktualizací zálohovat.

## EN
### What's new in 1.1.7
- **Fixed: golems stuck while transforming.** A golem that got a move order in the middle of its transformation (cocoon), e.g. from an order to a whole selected group, stayed half-transformed on one tile, kept flipping between cocoon and walking and could not be moved, disbanded or destroyed. A running transformation can no longer be interrupted, and golems stuck like this in older saves recover on their next order.
- A golem waiting for a blocked path no longer flips in and out of obelisk mode.

### What's new in 1.1.6
- **Optional skirmish turbo mode**: a new RULES option in the skirmish setup – ORIGINAL / TURBO (3× mana and XP, +2 golems) / BLITZ (6×, +4 golems) / CUSTOM (turbo_* values in bamport.ini). Both sides get the same boost. Campaign and network games always use the original rules; the default is ORIGINAL.
- **Fixed: a Basal Golem stuck on the portal** kept flipping in and out of obelisk mode and could not be moved or disbanded. It happened with auto-summon when the portal was ringed by meditating golems. A golem walled in on all sides is now left alone, and automatic production no longer picks golems that cannot move.

### What's new in 1.1.5
- **Fixed: crash when double-clicking a unit** (select all of that type) while one of them was under the game's own control.

### What's new in 1.1.4
- **Smarter enemy AI**: golems no longer walk alone into the enemy base or join counter-attacks, stop making pointless trips to the portal and wait for mana at a building instead of giving up the transformation — the AI now builds more units and keeps a bigger army. Defenders stop shuffling between buildings and defend the one under attack. Build crews no longer go to foundations in the enemy base. Units guarding strategic points no longer wander to the map corner and hold the point for a while.
- **Better pathfinding**: units no longer take dead-end detours, no longer stop one tile short after a retreat, and a unit in the way steps aside instead of possibly being destroyed.
- **Automatic production**: select a building (e.g. barracks) and **right-click the transform button** — each click cycles to the next researched unit, then off. Idle golems walk over and transform on their own; at least 4 golems are always kept. The building gets a gold frame and a gem marker.
- **Q key** toggles automatic golem summoning.
- **Shift + number** adds the selected units to an existing control group (Ctrl + number).
- **Fixed**: game speed couldn't be changed after loading a save from the main menu.
- New controls are listed in the help (F1).
- Mid-mission saves from an older version can't be loaded; the campaign continues from the start of the current mission (Single Player → Continue). Back up your saves before updating.
