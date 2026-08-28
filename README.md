# Shadowgate: The Dark Ascent

A two-episode hardcore web remake of the 1987 NES classic. Built in vanilla HTML/CSS/JS, no dependencies, runs entirely in the browser.

## Play

Open `index.html` in any modern browser. Click to start.

## What it is

**Episode I — Castle Shadowgate**
- 18 rooms: Gatehouse through the Warlock Lord's Chamber
- Torch mechanic: burns in real time, extra torches extend your run, out of light = dead
- Puzzle chain: chapel candle sequence → skull key → crypt → oracle riddle → dragon fight → troll toll → sanctum gem socket → Talimar boss (BIND then DESTROY with Crystal Vial)
- Ritual timer on the final boss: ~55 seconds to execute the sequence
- NES-style chiptune music (square wave + triangle bass)
- Items float visibly in the 3D perspective scene; click anything for a context menu

**Episode II — Gates of the Abyss**
- Unlocks after defeating Talimar; you fall through the floor into the Underdark
- 10 new rooms with a tighter puzzle chain
- Bucket puzzle: fill at the Underground River, douse fire in the Flooded Passage
- Spider Chamber, Alchemy Lab, Menagerie (raven + snake), Void Antechamber
- Boss: Malachar the Void-Born — incorporeal until you use the Void Crystal, then BIND, then Alchemy Bomb
- Ritual timer: ~65 seconds

## How to die (partial list)

- Open the wrong sarcophagus in the Crypt
- Cast SUMMON anywhere
- Cast DESTROY on Talimar before BIND
- Charge the dragon with just the sword (no Dragon's Bane)
- Walk into the Spider Chamber web before burning it
- Use the empty bucket on the fire
- Touch Malachar without the Void Crystal
- Run out of torches in the dark
- Let either ritual timer reach zero

## Tech

Single-file HTML. Canvas 2D perspective renderer. Web Audio API for chiptune and SFX. No frameworks, no build step, no server required.

## Status

Work in progress. Playable but rough in places.
