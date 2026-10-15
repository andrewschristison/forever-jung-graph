# Setup: local models

Running the companion on your own machine means nothing you type leaves it, which is the most private setup there is. The trade-off is context: the seventeen files together are roughly 790 KB of JSON, far more than most local models can hold in one window. You need retrieval, or a smaller set of files.

## The simple way

1. Use a local chat app that supports a system prompt and a document collection. Open WebUI (with Ollama), LM Studio, and Jan all do; so do most retrieval-augmented setups.
2. Paste the full prompt from [`SYSTEM_PROMPT.md`](SYSTEM_PROMPT.md), the text between the two rules, as the **system prompt**. In Ollama alone, put it in a Modelfile:

   ```
   FROM llama3.1
   SYSTEM """
   (paste the prompt here)
   """
   ```

   then `ollama create forever-jung -f Modelfile`.
3. Add the files from `knowledge-graph/` to the app's **knowledge** or **documents** collection so they are retrieved per question rather than loaded whole. If your app has no retrieval, attach only `concepts.json` and `symbols.json` (about 430 KB together) and expect a model with a large window.
4. Run the limits check from the [companion README](README.md). Smaller models drop instructions more easily; if the check fails, shorten the prompt to the version at the foot of `SYSTEM_PROMPT.md` and keep it near the top of the context.

## Notes

- Choose a model that follows system prompts well. The companion's value is in the restraint (one question, no verdicts, the limits), and a model that ignores instructions will not deliver it.
- For memory across sessions, keep a plain-text dream journal file and add it to the same document collection. The companion can then watch what changes over months, which is where the method pays off.
- The code in this file is MIT licensed; the data and the prompt are CC BY-NC-SA 4.0. See the two LICENSE files at the repository root.
