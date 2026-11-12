# caivman plugins

The three recipe books for a caivman brain. They install into Claude Code in two commands and update themselves when this repository changes.

| Plugin | What it does | Chapter of the guide |
|---|---|---|
| `capture` | Reads your brand files, best work and emails; writes brand, voice, standards and sources; builds your Word and PowerPoint templates | 1 |
| `wrap-up` | "Note that" mid-session and "wrap up" at the end: files what the session taught and saves it to GitHub | 3 |
| `first-skill` | Picks one routine job and turns it into a written method Claude follows every time | 4 |

## Install

In a Claude Code session, inside your brain folder:

```
/plugin marketplace add tmmetricadvisory/caivman
/plugin install capture@caivman
/plugin install wrap-up@caivman
/plugin install first-skill@caivman
```

Then switch on updates once: `/plugin`, Marketplaces tab, select caivman, Enable auto-update. New versions arrive at the start of your next session. To fetch them sooner: `/plugin marketplace update caivman`.

## What these plugins do not do

They read your brain folder and write into it. They do not send anything anywhere else, and they never send, pay, post or sign on your behalf. Every one is plain text; ask Claude to read any of them to you.

## The brain they expect

A folder made from the [caivman starter](https://github.com/tmmetricadvisory/caivman-starter): `CLAUDE.md`, `context/`, `bench/`, `clients/`, `memory/`, `.claude/skills/`. The guide that walks you through it: [caivman](https://claude.ai/artifact/9xkQ2Gv8KfZkaQCYkPbn6y).

## What's new

See `CHANGELOG.md`. The first line is what the guide shows under "what's new".
