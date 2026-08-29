# Saving Throw

Roll a d20, resolve what comes up, pass the die left. That is the whole loop.
Most results are over in seconds; a few stick around and quietly rewrite how
the rest of the night plays.

**Players:** 3+ (several results need a left, a right, and an across)
**You need:** a d20, drinks
**Length:** as long as you like — there is no end condition

## The unit

**One hit = 2 sips.** Everywhere the table below says "drinks 2", that means
two sips, not two drinks. A Natural 20 handing out 5 is five sips.

## The table

| Roll | Name | Effect |
|:---:|---|---|
| 1 | Critical Fail | You drink 2 |
| 2 | Left | Person on your left drinks 2 |
| 3 | Right | Person on your right drinks 2 |
| 4 | Across | Person across from you drinks 2 |
| 5 | Your Choice | Anyone you name drinks 2 — **or** dare them instead: they do it and drink nothing, they duck it and drink 4 |
| 6 | Everyone | Everyone drinks 2 |
| 7 | Waterfall | All start drinking; you stop when you want, each player can only stop once the person on their right has |
| 8 | Categories | Name a category, go round the table, first to stall or repeat drinks |
| 9 | Rule Maker | Invent a rule, holds until your next turn, break it and drink |
| 10 | Duel | Pick someone, both roll, lower drinks 2, tie means both |
| 11 | Deflect | Immune until your next turn |
| 12 | Thumb Master | Thumb on the table any time; last to follow drinks |
| 13 | Truth or Drink | Answer the question or drink |
| 14 | Two Truths and a Lie | Table guesses; wrong guessers drink, or you drink if they all get it |
| 15 | Reverse | Play direction flips and left/right invert for the rest of the game; another 15 flips it back |
| 16 | Initiative | Die goes once round, everyone rolls, lowest drinks 2, ties reroll |
| 17 | Double Tap | Reroll and apply the result to two people |
| 18 | Most Likely To | Table points, most fingers drinks |
| 19 | Squire | Nominate someone permanently — whenever you drink, they drink. Only a new 19 reassigns. Chains resolve downhill |
| 20 | Natural 20 | Either everyone else drinks, or hand 5 to one person. Immune until the die returns to you |

## Substituting a dare

Roll a **5** and you have two ways to spend it:

- **Name someone and they drink 2** — the plain version, unchanged.
- **Dare them instead.** They do it and they drink **nothing**. They refuse and
  they drink **4** — two hits instead of one.

That is a live decision on both sides. Daring is a gamble for you: pitch it too
soft and they will just do it and walk away dry. It is a squeeze for them:
take the dare, or take double.

Two things to hold to, or 5 stops being fun:

- **The dare happens now, at the table.** If it needs leaving the room, a phone,
  or another person's involvement, it is not a dare, it is a side quest.
- **Refusing is always allowed.** The 4 is the entire penalty — nobody is
  obliged to do anything, and "no" costs exactly four sips and nothing else.

If 4 is not enough teeth for your table, raise the refusal rather than removing
the right to refuse.

## The two that drift

Most results resolve and vanish. **15** and **19** do not — they are what make
the table state wander over the course of a night.

**15 — Reverse.** Play direction flips, and so do left and right. That means
**2** and **3** now point at different people than they did a minute ago, and
**7 (Waterfall)** chains the other way round the table. It holds until someone
rolls another 15, which flips it back. Two 15s do not stack into anything —
they just undo each other.

**19 — Squire.** Permanent, and the only thing that clears it is somebody else
rolling a 19. Because squire links persist, they **chain**: if A squires B and
B squires C, then A drinking makes B drink, which makes C drink. Resolve those
**downhill** — follow the links away from whoever drank first, and stop when
you reach someone who has no squire.

Worth knowing before it happens: nothing in the rules prevents a **loop** (A
squires B, B squires A). Agree up front whether a chain fires once per link or
whether you cap it, or you will be arguing about it at 1am.

---

> **Still to add:** the game's two files were never pushed and are not in this
> repo yet.
>
> ```
> games/d20-saving-throw/rules.json     outcome table, editable
> games/d20-saving-throw/roller.html    browser roller
> ```
>
> If `roller.html` loads `rules.json` by a relative path it will still work —
> the two sit side by side in this directory. Only a path reaching up out of
> the old repo root needs editing.
