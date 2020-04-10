Minions are a feature in Old School Bot that let you simulate playing a virtual runescape account in discord. You control a minion, who you send out to do various tasks, like killing monsters for loot, completing clue scrolls, and training skills. With the loot they get, you can craft items, sell them and trade to other real players.

> Minions are entirely virtual, and not in any way tradeable for real GP or real money. It's simulating the real game for fun. We strictly do not allow any bot users to break any of the official OSRS rules. Read the rules here: [Old School Bot Rules](https://www.oldschool.gg/oldschoolbot/rules)


# Skills
Start of with `+minion buy`
You can view your minions' stats using `+m stats`.
- `+m pat` | pat your minion
- `+m kill <Npc_name>` | Kill command
- `+k <npc_name>` | short kill command

## Skillcapes

If you reach level 99 in a skill, you can purchase a skillcape for 99k by typing `+skillcape <skill_name>`. If it's your first 99, you'll get an untrimmed cape.

Possible cape's
- Agility
- Fishing
- Mining
- smithing
- firemaking
- quest-points

## Mining

You can train mining using `+mine [quantity] <ore>`, for example `+mine 10 coal`.

### Ores

| Ore Name | Nuggets | Minerals | Level |
| - | :-: | :-: | :-: |
| Rune essence |  |   | 1 |
| Copper ore |  |   | 1 |
| Tin ore |  |   | 1 |
| Iron ore |  |   | 15 |
| Silver ore |  |   | 20 |
| Pure essence |  |   | 30 |
| Coal |  |  ✔ | 30 |
| Gold ore | ✔ |   | 40 |
| Mithril ore | ✔ |   | 55 |
| Adamantite ore | ✔ |   | 70 |
| Runite ore | ✔ |   | 85 |
| Amethyst |  |  ✔ | 92 |

*note: iron ore there is only a 50% chance that you will be able to get a bar out of it

## Other smithing require's
- You can now `+buy Goldsmith gauntlets`, with 25 QP. They provide a boost to smithing gold ore exact same as ingame. Simply having it in your bank will give you the boost.
- Added the 3 sets of mining gloves (+create mining gloves for example). They give 2%, 4% and 6% speed boosts.
- `+create mining gloves` - 60 unidentified minerals.
- `+create Superior mining gloves` - 120 unidentified minerals.
- `Expert mining gloves` - + extra 60 unidentified minerals to combine

80 smithing req:
- `+create godsword blade`, `+create armadyl godsword | Bandos | Zamorakian | Saradomin`
85 smithing req:
- `+create Infernal pickaxe` (Dragon_pickaxe + Smouldering_stone + 85 Smithing)
- `+create the shield wards` (odium,  malediction)
- `+open caskets Normal casket` - no clue casket
- `+create dragon + dragonfire ward` (+anti-dragon shield)

*Prospector outfit:* 
- `+create prospector helmet` - 40 Gold nuggets
- `+create prospector jacket` - 60 Gold nuggets
- `+create prospector legs` - 50 Gold nuggets
- `+create prospector boots` - 30 Gold nuggets

*180 golden nuggets for full set

# Woodcutting & Firemaking 
- Simple, you chop tree, get log, get boost for axes. `+chop logs` to start! 
- Works as you'd expect, you can do `+chop 10 logs` to chop only 10, etc
- Axe boosts are as follows: Dragon axe 9%, Infernal axe 11%, Gilded axe 12%, 3rd age axe 13% - simply having them in the bank, and having atleast 61 WC, will give you the boost automatically.
- You can buy a woodcutting cape like normal, `+skillcape woodcutting`
Woodcutting Logs:

- Level 1: Logs
- Level 1: Achey Logs
- Level 15: Oak Logs
- Level 30: Willow Logs
- Level 35: Teak Logs
- Level 45: Maple Logs
- Level 45: Bark
- Level 50: Mahogany Logs
- Level 54: Arctic Pine Logs
- Level 60: Yew Logs
- Level 65: Sulliusceps
- Level 75: Magic Logs
- Level 90: Redwood Logs

**Firemaking**

- To train firemaking, you just +light <quantity> <logname> or just +light <logname> for example, `+light logs` - thats all there is to it.
- You can buy the skillcape like all other skills, +skillcape firemaking at lvl 99
  
## Bank command
- +bank / +bank 2 / +bank 3 / +bank 4 | - Bank page's
- +bank —search=item | Search for item in bank
- +bank —sv | Bank value
- +bank —text | Discord file
- +bank —text —full    |    .txt Download file
- +bank —full     |    full bank

 # Fun & clue scroll command
- `+drop` | Drop items like untradeable or stuff you dont want
- `+duel @<player_name>` | to duel
- +sellto @<Player_name> - sell your products | `+sellto @<player_name> 100m 5 Bandos tassets`  - you have 20 seconds to decide  > (confirm). 
the buyer must confirm the purchase with: `buy`
- +pay @<Player_name> | send money to another person
- `+cl beginner` | easy | medium | hard | elite | master
- `+cl clues rare` voor rare clue rewards
- `+minion clue 1 [clue type]` | Solve a clue
- `+m clues` | shows clue log

- You get your minion to do the clue using `+m clue <tier>` , e.g. `+m clue easy`

## Ironman Mode
- You become an ironman by doing `+m ironman`
- When becoming an ironman, your ENTIRE account, bank, collection log, GP, etc will all be reset to blank/empty.
- Ironman works like you'd expect, cant trade, sell, etc. Also cant get GP from dailies.
- If your minion is an ironman, it'll have the icon next to its name.
- Ironman-only leaderboards will be added.
- You can de-iron, like ingame, you keep all your stuff and simply just lose the grey helmet icon. To do so, just `+m ironman` again.
