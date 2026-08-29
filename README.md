# saving-throw

A small collection of drinking games. One folder per game — rules in each
folder's README, plus any files the game needs to run.

## Games

### [Saving Throw](games/d20-saving-throw/) 🎲

Roll a d20 against a target number and drink when you fail the save. Ships with
a browser-based roller (`roller.html`) driven by an editable `rules.json`, so
you can retune the outcomes without touching any code.

*Rules and files not yet added — see the folder.*

### [Horse Race](games/horse-race/) 🐎

Four aces are horses, a line of face-down cards is the track. Everyone draws a
card: the suit picks your horse, the number is your stake. Flip the deck and
your horse runs on its own suit. Back the winner and you hand out drinks — back
a loser and you drink your own. Needs one deck and no setup beyond dealing.

## Layout

```
README.md                    this file
games/
  d20-saving-throw/
    README.md                rules
    rules.json               outcome table
    roller.html              browser roller
  horse-race/
    README.md                rules
```

Adding a game means adding a folder under `games/` with a `README.md`, and a
short entry in the list above.
