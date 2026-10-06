# WoW Forever Survival Hunter Gameplay Sim

A browser sim for practising the level 60 melee Survival Hunter rotation in World of Warcraft: Forever. You press the abilities; the sim auto-attacks a raid boss dummy with both weapons, tracks mana and cooldowns, and shows a damage breakdown when the dummy dies.

**Play it:** https://wowf-gameplay.github.io/hunter-gameplay-sim/

## Features

- Raptor Strike (queued on the next swing), Mongoose Bite lit up by Expose Prey, Strider Kick, Immolation Trap, Wing Clip, Rapid Fire, Blood Fury and Major Mana Potion
- Lone Wolf with no pet, Deadly Aspects Quick Strikes procs, Lacerating Strikes bleed, Predator's Edge, Resourcefulness, Iceblade Hacker's Frost damage, Windfury Totem and Crusader
- Mana with the five-second rule, Judgement of Wisdom and raid regeneration buffs
- Toggles for raid buffs, consumables and boss debuffs
- Gear and talent tabs, plus a Stats tab for entering your own character stats
- Rebindable keys (with Shift/Ctrl), adjustable dummy health, and a Warcraft Logs-style end-of-fight breakdown

## Setup

The default gear, enchants and 5/11/35 talent build follow the [MythicSim](https://mythicsim.com/wow-forever/tier-list) Survival Hunter preset, which fights in melee with an axe and a dagger. Mechanics follow the open-source engine MythicSim is built on and Forever beta tooltips, and may change as the beta does.

Two notes on the defaults: Trueshot Aura is part of the MythicSim preset but their engine does not apply it, and Curse of Recklessness is applied here but not there, so with everything on this sim reports a little more damage than the MythicSim figure. Turn both off to compare like for like. Mongoose Bite's flat damage is fitted to MythicSim's results, which are well above the tooltip's 57. The Goblin Sapper Charge is not simulated.

## Running locally

It is a single file with no build step: open `index.html` in a browser. Ability icons load from Wowhead's image server, so they need an internet connection.

## Related

- [All sims](https://wowf-gameplay.github.io/)
- [Warrior gameplay sim](https://github.com/wowf-gameplay/warrior-gameplay-sim)
- [Paladin gameplay sim](https://github.com/wowf-gameplay/paladin-gameplay-sim)
- [Shaman gameplay sim](https://github.com/wowf-gameplay/shaman-gameplay-sim)
- [Druid gameplay sim](https://github.com/wowf-gameplay/druid-gameplay-sim)
- [Rogue gameplay sim](https://github.com/wowf-gameplay/rogue-gameplay-sim)

## Disclaimer

Fan project, not affiliated with Blizzard Entertainment. World of Warcraft is a trademark of Blizzard Entertainment, Inc.
