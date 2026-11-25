# Project Proposal

**Name:** Caleb W.
**Project:** Escape Room Adventure
**App name:** Abandoned Grounds
**Repo link:** https://github.com/IsntCaleb/csc110-final-project

## My idea in two sentences
Abandoned Grounds is an escape-room game for anyone who likes puzzles. The player wakes up in an abandoned
coffee shop they fell asleep in and has to explore the rooms, collect items, and solve puzzles to find a way out.

## My twist / theme
It's set in an old coffee shop that's been abandoned: dusty counters, broken espresso machines, and locked doors.
The puzzles use coffee-shop things, like a recipe card that gives you a code, the cash register, and the espresso machine.
I picked this because I like games and coffee, so this mixes both.

Rough room ideas (these may change in the plan): the café floor, the front counter, the kitchen, the storage room,
and the manager's office, with the back door as the exit.

## Requirements checklist
- [ ] At least 5 connected rooms, 3 usable items, and 3 puzzles
- [ ] Show the room description, available exits, and discovered clues
- [ ] Collect items, use items, move between rooms, and enter puzzle answers
- [ ] At least one item unlocks access (for example, a key opens a locked door)
- [ ] At least one puzzle depends on an earlier discovery
- [ ] Clear feedback for invalid moves, unavailable items, and incorrect actions
- [ ] A solved puzzle cannot give its reward again
- [ ] Inventory search by name, or a puzzle filter by solved status
- [ ] Progress summary based on what the player actually discovered
- [ ] A reachable escape ending that requires all 3 puzzles to be solved
- [ ] Save and reopen the current room, inventory, puzzle states, and changes to the world
- [ ] Data stored in classes/objects and `ArrayList`s, and kept consistent when things change
- [ ] Ship a sample save file in `data/` so the instructor can test

## The 60-second demo I imagine
I start a new game and the player wakes up on the café floor. I try a locked door and get a "the door is locked"
message, then pick up a key and use it to open the door. I find a recipe card, which is a clue, and use the code
on it to solve a puzzle. Then I save, close the app, and reopen it to show I'm in the same room with the same
inventory. I finish the last puzzle and escape through the back door, and the end screen shows my progress
summary.

## One stretch goal (if time allows)
A countdown timer. The player has a set amount of time to escape the coffee shop before time runs out.

## My biggest worry
I'm most worried about file saves and loads.
