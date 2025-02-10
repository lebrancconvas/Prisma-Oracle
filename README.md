# Prisma Oracle

## Author

Poom Yimyuean ([@lebrancconvas](https://github.com/lebrancconvas))

## Overview

Board Game that each player uses their only one monster to fight and deal with their monster's guilty.

## Materials

- Monster Card x2 (For each player)
- Number Card Deck (Recommended 0-20)
- Guilty Point Token

## Rules

- Each player select their own monster and place on the monster's base.
- Rock-Paper-Scissors (or whatever) to choose who begin their turn first.

### Player Turn

- **Draw Phase**
  - Opponent has their opportunity to draw 2 number cards first.
  - Then player draws their 2 number cards.
- **Ajar Phase**
  - Opponent select to reveal 1 of their cards to player.
- **Decide Phase**
  - Then player decides to "Fight" or "Dodge".
- **Reveal Phase**
  - After that, All players reveal all their number cards.
- **If Player selected "Fight" (Combat Phase - Fight)**
  - Player Number > Opponent Number: Opponent's Monster got 1 Guilty Point.
  - Opponent Number > Player Number: Player's Monster got 1 Guilty Point.
  - Player Number == Opponent Number: Return all numbers to deck shuffle and draw and reveal and decide once more. If this happen again the turn will end automatically.
- **If Player selected "Dodge" (Combat Phase - Dodge)**
  - Player Number > Opponent Number: Player's Monster got 1 Guilty Point.
  - Opponent Number > Player Number: Opponent's Monster got 1 Guilty Point.
  - Player Number == Opponent Number: Return all numbers to deck shuffle and draw and reveal and decide once more. If this happen again the turn will end automatically.
- **End Phase**
  - Turn Ending.

## Winning Condition

- Player whose monster has 5 Guilty Points will lose and another player will win.

## Mechanic

- Each Monster has their own effect (skill) based on their Guilty Point(s) number.

## Data

### Monster Data

- Monster Name
  - English Name
  - Thai Name
- Monster Image
- Effect(s) / Skill(s)
  - Effect Name
  - At lease Guilty Point when want to use.
  - Effect
  - Number of Using in one duel / match.
