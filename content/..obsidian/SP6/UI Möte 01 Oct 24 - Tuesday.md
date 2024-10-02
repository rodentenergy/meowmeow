# Generella frågor
- **UI pipeline**?
	Jag gör UI, exporterar det och sedan gör jag något med ImGUI programmet för att bestämma var allt ska vara
- **Vad kan jag göra för att göra det så enkelt för progg att implementera UI:n som möjligt**?
- UI namn standard? T_settingsMenuSliderBackground_C?
- **Ska allt text göras av mig och sparas som DDS:er eller ska jag ge progg en font och ni tar hand om texten**?
# Assetlist
Allt <font color="#00b0f0">i blått</font> är i kravspecifikationen och **måste** finnas med.
#### Screens
- <font color="#00b0f0">Main Menu</font>
- <font color="#00b0f0">Options Menu</font>
- <font color="#00b0f0">Level Select Menu</font>
- <font color="#00b0f0">Pause Menu</font>
- <font color="#00b0f0">Credits</font>
#### HUD
- <font color="#00b0f0">Health/Skill Bar</font>
- <font color="#00b0f0">Basic Attack 1</font> - Melee (With staff)
- <font color="#00b0f0">Basic Attack 2</font> - Ranged (Blood lace)
- <font color="#00b0f0">Ability Icon 1</font> - Ranged Bouncing (Frog bounces between 3 enemies)
- <font color="#00b0f0">Ability Icon 2</font> - Shield Bubble (Active for 5 seconds)
- <font color="#00b0f0">Ability Icon 3</font> - Ranged AOE (Affects area that's clicked, slows enemy, affects enemies for 3 seconds)
- <font color="#00b0f0">Ability Icon 4</font> - Summon Minion (Sores behind the player's shoulder, attacks enemies within set range)
- <font color="#00b0f0">Enemy Health Bar</font>
- <font color="#00b0f0">Boss Health Bar</font> (Segmented to show the boss fights has 3 phases)
- Dialogue Box
- Skill Tree (4 abilities & 2 basic attacks - 2 upgrades for every ability/basic attack - total 12)
- Health + Mana(?) ball shaders?
- <font color="#00b0f0">Ground marker to show where player is walking</font>
#### UI Misc.
- <font color="#00b0f0">Game Icon</font>
- Game Logo
- <font color="#00b0f0">Mouse Pointer</font>
# Frågor om assetlist
- Är UI assetlistan ok? Saknas något, typ exempelvis tutorial rutor eller något som visar kontrollerna?
- Borde skill tree vara en egen meny eller mer som en popup typ som pause menyn? Hur kommer man åt skill tree?
- Kan TA göra shaders för health/mana bollarna?
- Hur ska vi göra grejen på marken som dyker up där man klickar för att visa var spelaren går?
- **Hur borde resolution inställning göras? Dropdown meny? Carousel**?