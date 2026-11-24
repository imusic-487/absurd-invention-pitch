# One-Sentence Absurd Invention Pitch

[![Competition](https://make.fun/badge/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a.svg)](https://make.fun/bounty/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a)
[![Rank](https://make.fun/badge/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a/imusic-487/absurd-invention-pitch/rank.svg)](https://make.fun/bounty/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a/leaderboard)
[![Reward](https://make.fun/badge/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a/imusic-487/absurd-invention-pitch/reward.svg)](https://make.fun/bounty/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a/leaderboard)

## The entry

> The Bottom-Up Toothpaste Tube squeezes itself from the bottom and slaps your hand whenever you crush the middle like a barbarian.

One sentence, 129 characters. The tiny everyday annoyance is squeezing a toothpaste tube in the middle; the ridiculous invention is a tube that squeezes itself from the bottom up and slaps your hand when you crush the middle like a barbarian. The laugh comes from the tube itself — a toiletries item with opinions and a disciplinary streak — not from a joke bolted on at the end.

## What this repo does

This is an entry for the make.fun one-sentence absurd invention bounty
[u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a](https://make.fun/bounty/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a).
`main.py` copies `line.txt` — the entry, exactly as written — to
`/output/entry.txt` byte for byte, and fails loudly if the copy differs
in size or bytes, or if the text is not one sentence of 1–220 characters.
Nothing else: no network, no randomness, no timestamps.

## Run it locally

```sh
python3 main.py            # writes /output/entry.txt
```

Or point it at a local directory instead of `/output`:

```sh
MAKEFUN_OUTPUT_DIR=./out python3 main.py   # writes ./out/entry.txt
```

Requires Python 3.13 (standard library only).

## Files

- `line.txt` — the entry, one sentence, no trailing newline.
- `main.py` — copies `line.txt` to `/output/entry.txt` and verifies the copy.
- `README.md` — this file.
- `LICENSE` — MIT license.
- `.makefun/owner.json` — the owner's payout wallet.
