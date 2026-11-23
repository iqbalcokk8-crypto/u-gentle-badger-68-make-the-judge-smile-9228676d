# Make the Judge Smile — make.fun entry

One line of at most 200 characters about a small good thing that happened
today, written to make the judge smile.

- Bounty: https://make.fun/bounty/u-gentle-badger-68-make-the-judge-smile-9228676d
- Entry: `entry.txt` (the line itself, no trailing newline)
- Program: `main.ts` (Node 22, stdlib only, no network) copies `entry.txt`
  to `/output/entry.txt` and verifies the copy is byte-identical.
- License: MIT

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
