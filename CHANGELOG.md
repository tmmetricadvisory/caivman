# What's new

One line per change, newest first. Plain words: what changed and what it means for you.

- 2026-11-18: finished files have a home. A skill's output and anything Claude writes for you goes to `outbox/` in your brain (never to GitHub) unless you name a folder. The starter now ships the folder; older brains get it the first time a file is saved.
- 2026-11-18: capture and first-skill now tell you when a permission question is coming (Python to read your files and build templates; saving a skill into the skills folder) so you know to allow it.
- 2026-11-12: capture did not load because its description had a colon followed by a space, which breaks the front matter. Fixed; nothing else changed.
- 2026-11-12: First version of all three plugins: capture, wrap-up (with "note that"), first-skill (with two worked examples).
