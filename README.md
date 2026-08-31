# saving-throw

A small collection of drinking games. One folder per game — rules in each
folder's README, plus any files the game needs to run.

## Games

### [Saving Throw](games/d20-saving-throw/) 🎲

Roll a d20, resolve the result, pass the die left. Twenty outcomes running from
a plain "you drink" up to Waterfall, Rule Maker and Thumb Master. Several refuse
to resolve neatly: Volunteer sends 1 a head round the table on and on until
somebody takes a 5 to end it, and Reverse and Squire persist outright, so the
table's shape drifts as the night goes on. One hit = 2 sips.

*Rules written up; `rules.json` and `roller.html` still to be added.*

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
    prompts.md               prompt lists for 8, 13 and 18
    rules.json               outcome table
    roller.html              browser roller
  horse-race/
    README.md                rules
```

Adding a game means adding a folder under `games/` with a `README.md`, and a
short entry in the list above.
