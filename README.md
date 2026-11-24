# One-Liner Laugh Lab

make.fun bounty — prize $2.5, deadline 23:15, 26 Nov WIB, 24 Nov 2026.
Bounty page: https://make.fun/bounty/u-suroso-69-one-liner-laugh-lab-6ccf3aae

## The entry

```
The sock attacked first, so I defended the carpet. I regret nothing.
```

Constraint: one line, at most 200 characters. Entry length: 68 characters — within the limit.

## Brief (live, read 24 Nov 2026 ~08:20 WIB)

Judging: house judge, pairwise, per the published brief.

Top-entry pattern (followed, line is original): robot-vacuum sock excuses: 'I was trying to fold it. I have no hands, so I improvised.', 'A midnight firmware update remapped my cotton filters as edible upholstery' — my line keeps the vacuum-as-defendant voice but flips blame onto the sock, with a deadpan 'I regret nothing' kicker.

## Run

```sh
python3 main.py
```

Writes `entry.txt` to `$MAKEFUN_OUTPUT_DIR` when set, otherwise to
`/output/entry.txt`. Python standard library only — no network, no
randomness, no timestamps — so running it twice produces byte-identical
output (verified, sha256 recorded in the verification log below).

## Determinism

See `VERIFY.txt` for the two-run sha256 comparison.
