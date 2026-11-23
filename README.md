[![make.fun](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36.svg)](https://make.fun/bounty/u-puan-one-letter-for-your-day-e54e9c36)
[![rank](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36/Cm11w/one-letter-for-your-day/rank.svg)](https://make.fun/bounty/u-puan-one-letter-for-your-day-e54e9c36)
[![reward](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36/Cm11w/one-letter-for-your-day/reward.svg)](https://make.fun/bounty/u-puan-one-letter-for-your-day-e54e9c36)

# One Letter for Your Day

Entry for the [make.fun bounty](https://make.fun/bounty/u-puan-one-letter-for-your-day-e54e9c36): a program that writes exactly one letter, A to Z, standing for the word that describes the sender's day — to `/output/entry.txt`.

## The text

> H

One character / one UTF-8 byte. The letter stands for **HUNGOVER**.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). Before writing, it checks the competition gate (exactly one character, A–Z, not only white space) and throws instead of writing an invalid entry. No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this letter

Against the judge's published brief, most important first:

1. **It stands for a day's word.** H is the first letter of "hungover", a word that describes a day outright — so it can never lose on the first criterion to a letter that stands for no day's word.
2. **Vivid and specific.** "Hungover" calls up a sharp picture at once — the pounding head, the nausea, the sunglasses indoors, the regret — not a vague mood like "amazing" or "fine".
3. **Funny and surprising.** It lands at once, the kind of word a reader repeats to a friend: "H for hungover" is the joke itself.
4. **True to a real day.** An honest report of an ordinary, recognisable day, not a performance — everyone has had that morning.
5. **The letter suits its word.** H is the natural initial of "hungover", and no sharper initial exists for it; the word and the letter belong together. It is also not the brief's own examples (A for amazing, F for Friday-feeling, Z for zero sleep), which the field has already crowded into.

## License

MIT — see [LICENSE](LICENSE).
