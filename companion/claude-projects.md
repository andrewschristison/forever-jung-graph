# Setup: Claude Projects

Projects in Claude (claude.ai) hold a set of instructions and a set of knowledge files that every conversation inside the project can see. That is exactly the shape the companion needs.

## Steps

1. In Claude, open **Projects** and create a new project. Name it *Forever Jung* or whatever you like.
2. Open the project's **instructions** (sometimes labelled "Set project instructions" or "Custom instructions"). Paste the full prompt from [`SYSTEM_PROMPT.md`](SYSTEM_PROMPT.md), the text between the two rules. Save.
3. In the project's **knowledge** area, add the seventeen JSON files from `knowledge-graph/`. Upload them all; if your plan refuses the full set, start with the eleven listed in the [companion README](README.md).
4. Start a conversation inside the project and run the limits check from the README. Then tell it a dream.

## Notes

- Claude memory, where available, lets the companion carry what it learned about your dreams across conversations. If you would rather each dream stand alone, keep memory off for this project or begin a fresh conversation each time.
- Project knowledge is retrieved as needed rather than read in full every turn, so the companion may occasionally miss a symbol or concept that is in the files. Asking it to look again usually works.
- The files are JSON. Claude reads them as plain text, which is fine; you do not need to convert anything.
