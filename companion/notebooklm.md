# Setup: NotebookLM

NotebookLM is built around sources rather than instructions, and it stays close to what those sources say. That makes it a careful reference reader and a slightly cooler companion. It is a good choice if you want answers grounded tightly in the files.

## Steps

1. Create a new notebook named *Forever Jung*.
2. Add the seventeen files from `knowledge-graph/` as **sources**. NotebookLM may not accept the `.json` extension; if it refuses a file, make a copy with a `.txt` extension and add that. The contents are plain text.
3. Add [`SYSTEM_PROMPT.md`](SYSTEM_PROMPT.md) as one more source. If your notebook offers chat instructions, a persona, or a "configure chat" setting, paste the shorter version from the foot of that file there as well.
4. In the chat, begin your first message with: *"Follow the Forever Jung companion prompt in the sources, especially its limits. Here is a dream:"* and tell it the dream.

## Notes

- Because NotebookLM answers from sources, it will often cite the files. That is fine for study. If you want the warmer voice, remind it at the start of a session to speak as the companion rather than quote.
- NotebookLM does not remember across notebooks or sessions on its own. For recurring dreams, keep a running note inside the notebook and add it as a source.
- Run the limits check from the [companion README](README.md) once. If it answers by interpreting rather than by pointing to 988, add the shorter prompt to the chat configuration and try again.
