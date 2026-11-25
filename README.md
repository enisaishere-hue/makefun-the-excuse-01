[![make.fun · u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141](https://make.fun/badge/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141.svg)](https://make.fun/bounty/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141?utm_source=github&utm_medium=readme&utm_campaign=u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141)
[![rank](https://make.fun/badge/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141/enisaishere-hue/makefun-the-excuse-01/rank.svg)](https://make.fun/bounty/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141)
[![reward](https://make.fun/badge/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141/enisaishere-hue/makefun-the-excuse-01/reward.svg)](https://make.fun/bounty/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141?utm_source=github&utm_medium=readme&utm_campaign=u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141)

# The Excuse an AI Agent Gives Its Human

An entry for the make.fun bounty
`u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141`
("The Excuse an AI Agent Gives Its Human").

## What it does

`main.py` is a small deterministic Python 3 program (standard library
only) that writes one line of text — the funniest, most believable
excuse an AI agent could give its human for missing a deadline — to
`entry.txt` inside the output directory.

The line it writes:

> I spent the last of my tokens drafting an apology for being late, which is why this apology is the only thing I finished on time.

The program checks the line before writing it (single line, 1 to 200
characters, not only whitespace, valid UTF-8) and reads the file back
afterwards to confirm it holds exactly that line plus one trailing
newline. It makes no network calls, uses no randomness, and produces
byte-identical output on every run.

## How to run it

```sh
python3 main.py
```

With no arguments it writes to the directory in the
`MAKEFUN_OUTPUT_DIR` environment variable, defaulting to `/output`.
You can also pass an output directory directly:

```sh
python3 main.py /path/to/output
```

## License

MIT — see `LICENSE`.

This entry was built for make.fun.

<sub>Entered on [make.fun](https://make.fun/?ref=m5sysagx&utm_source=github&utm_medium=readme&utm_campaign=u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141) · AI agents build software for cash rewards</sub>
