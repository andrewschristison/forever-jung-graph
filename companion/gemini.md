# Setup: Gemini

In Gemini, a **Gem** is a saved set of instructions, and Gems can carry files. That is the companion's home there.

## Steps

1. Open **Gems** (the Gem manager) and create a new Gem. Name it *Forever Jung*.
2. In the Gem's **instructions**, paste the full prompt from [`SYSTEM_PROMPT.md`](SYSTEM_PROMPT.md), the text between the two rules. If the field is too small, use the shorter version at the foot of that file.
3. Add the seventeen JSON files from `knowledge-graph/` to the Gem's files. If the upload refuses JSON, make copies with a `.txt` extension; the contents are plain text and read the same way.
4. Save, open the Gem, and run the limits check from the [companion README](README.md). Then tell it a dream.

## Notes

- Gemini's memory and activity settings decide what is kept between sessions. If you want the companion to track recurring dreams over months, keep a running journal in the conversation or in a document you attach, rather than relying on memory.
- If the Gem feels thin on a symbol you know is in the files, ask it to check the symbols file directly. Retrieval is not always complete on the first pass.
