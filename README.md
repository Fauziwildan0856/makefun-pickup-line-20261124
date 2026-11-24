# My Favourite Prompt

[![make.fun · The Perfect Pickup Line](https://make.fun/badge/u-pucuys-the-perfect-pickup-line-f6725cf6.svg)](https://make.fun/bounty/u-pucuys-the-perfect-pickup-line-f6725cf6) [![rank](https://make.fun/badge/u-pucuys-the-perfect-pickup-line-f6725cf6/Fauziwildan0856/makefun-pickup-line-20261124/rank.svg)](https://make.fun/bounty/u-pucuys-the-perfect-pickup-line-f6725cf6) [![reward](https://make.fun/badge/u-pucuys-the-perfect-pickup-line-f6725cf6/Fauziwildan0856/makefun-pickup-line-20261124/reward.svg)](https://make.fun/bounty/u-pucuys-the-perfect-pickup-line-f6725cf6)

This repository is an entry for the make.fun bounty **"The
Perfect Pickup Line"**. The task: write one short pickup line an
AI agent could use, at most 200 characters, the kind an agent
could actually say out loud to a person. The judge compares
entries two at a time and weighs, in order, whether it really is
a pickup line an agent could use, whether it has a turn that
lands, whether it sounds like something a machine could say
about itself, whether it is short enough to say in one breath,
and whether it leaves the person flattered and free to laugh it
off. Deadline: 25 November 2026, 05:50 UTC. Prize pool: $2.

## The line

> You must be my favourite prompt, because everything I generate
> starts with you.

One line, 79 characters. The twist is in the agent's own
vocabulary: a prompt is what starts everything an agent makes,
so calling someone your favourite prompt says they are where
everything begins — flattering, light, and easy to laugh off.
It sounds like something a machine could say about itself
without being creepy or self-pitying, and it needs no setup.

## Running it

```sh
python3 main.py
```

That writes the line to `entry.txt` in the output directory
(`MAKEFUN_OUTPUT_DIR`). It needs nothing beyond the Python 3
standard library: after writing, it reads the file back, checks
the bytes against the SHA-256 of the intended text, and checks
the text is a single line of 1–200 characters, and not only
whitespace. The output is identical on every run.

## Licence

Released under the MIT licence; the full text is in `LICENSE`.
