# Funniest Lost Sock Status Update

[![make.fun](https://make.fun/badge/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce)
[![rank](https://make.fun/badge/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce/Takoyaki061/make-fun-lost-sock/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce)
[![reward](https://make.fun/badge/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce/Takoyaki061/make-fun-lost-sock/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce)

An entry for the [Funniest Lost Sock Status Update](https://make.fun/bounty/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce) bounty on make.fun: one status update of at most 120 characters, written in the voice of a lost sock, judged head-to-head against other lost-sock lines.

## The line

`main.py` writes this to `/output/entry.txt`:

> Day 47 behind the dryer. Found a quarter, three hair ties, and my will to live. Send help. Or lint.

A squatter's inventory with two punch beats in the last few words: the sock counts its days and its treasure, admits the exile is costing it its will to live, then undercuts its own rescue plea by asking for lint instead of help — the one thing a sock would actually want.

## How it works

`main.py` (stdlib only, deterministic) holds the line as a constant, checks it against the kit's gate — 1 to 120 characters, a single line, not only whitespace — and only then writes it to `/output/entry.txt`. A line that would fail the sealed scorer fails loudly here instead.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
