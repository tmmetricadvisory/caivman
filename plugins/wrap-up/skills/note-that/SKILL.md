---
name: note-that
description: Saves one durable fact to the right file in a caivman brain, mid-session, the moment the person says it. Use whenever a message starts with or contains "note that", "remember that", "remember this", "save this", "make a note", "from now on", or "forget that" / "remove that" to take a fact out. Claude picks the file (a client's memory, the rulebook, the business file, the sources list, the never-share list), checks it is not already there, writes it, and confirms in one line where it went. Not for ordinary conversation, and not for the end-of-session routine, which is the wrap-up skill.
---

# Note that

"Note that" means: save this for good, now, without waiting for wrap up. Decide where it goes, write it, confirm in one line.

## 1. Work out what the fact is

Take the sentence after "note that" (or the thing the person is pointing at) and reduce it to one line of fact, in the person's words where possible. Keep the date if it is a decision. If it contains two facts, write two lines.

## 2. Pick the file

Use the first row that fits. Read the file before writing.

| The fact is about | File | Where in it |
|---|---|---|
| One client: what is live, what was agreed, who does what, what to avoid | `clients/<name>/MEMORY.md` | Live now, Agreed or Avoid. Create the folder from `clients/_template/MEMORY.md` if missing. |
| How the person likes things done, every time | `CLAUDE.md`, "How to work" | One short bullet. |
| Who the person is, their role, how they work | `context/me.md` | The matching line. |
| What the business does, sells, charges, runs on | `context/business.md` | The matching heading. |
| Where a document or folder lives | `context/sources.md` | A new row. |
| Something that must never leave the brain or appear in output | `context/never-share.md`, "Mine" | One line. |
| The brand, the voice or what good work looks like | `context/brand/brand.md`, `context/voice.md`, `context/standards.md` | A minimal edit in the file's style. |
| A step in a skill | `.claude/skills/<name>/SKILL.md` | The step concerned. |
| Something unfinished, for next time | Today's note in `memory/`, Open threads | One bullet. |

If none fits, ask once: "Where should that live: the rulebook, the business file, or a client?" Do not invent a new file or section.

## 3. Check before writing

- **Already there?** If the same fact is in the file, say "already noted" and stop.
- **Contradicts something there?** Replace the old line with the new one, dated, and say what it replaced. Two opinions never sit in one file.
- **Safe to store?** Never write bank BSB or account numbers, card numbers, passwords, keys, tokens, tax file numbers, or anyone's personal details beyond a name and a role. Say so in one line and offer "the account ending 123" instead.
- **Private?** Pay, performance, unannounced deals, legal matters: keep these in Claude's own memory for this folder rather than the shared brain, and say "kept private to you".
- **Size.** A client `MEMORY.md` stays under about 2,500 characters. If the new line would push it over, merge or remove the oldest resolved line first and say which.

## 4. Write it as a fact

Facts, never orders. "Future Proof invoices on the 1st, not month end (noted 12 Nov)", not "always invoice Future Proof on the 1st". A rule the person wants Claude to follow in every session goes in `CLAUDE.md` as one bullet, where it is reviewed.

## 5. Confirm

One line: `Noted in clients/future-proof (Agreed).` The file is saved to GitHub at wrap up; say that only if the person asks when it is backed up.

## Forget that

"Forget that", "remove that", "that's wrong, take it out": find the line, show it, and ask once before deleting it. Then confirm in one line.
