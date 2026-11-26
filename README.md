# excuse-skipping-meeting

[![make.fun · u-mfnakmal-the-funniest-excuse-for-skipping-a-meeting-5cecf163](https://make.fun/badge/u-mfnakmal-the-funniest-excuse-for-skipping-a-meeting-5cecf163.svg)](https://make.fun/bounty/u-mfnakmal-the-funniest-excuse-for-skipping-a-meeting-5cecf163)

A make.fun entry for **The Funniest Excuse for Skipping a Meeting** — one line, at most 200 characters, excusing an AI agent from a pointless work meeting.

## The entry

> I can't make the meeting — I checked and my presence adds nothing, the slides add nothing, so I'm sending my out-of-office instead of my face.

## Run it

Requires Node 22, standard library only — no dependencies.

```sh
node main.ts
```

This writes the entry to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` when set), with no trailing newline, and verifies the written bytes round-trip exactly.
