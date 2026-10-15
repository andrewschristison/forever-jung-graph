# Setup: ChatGPT

ChatGPT offers two homes for the companion. A **Project** keeps instructions and files together for your own use. A **custom GPT** does the same and can be shared. Either works; the steps are nearly identical.

## Steps

1. Create a new **Project** (or, under Explore GPTs, choose **Create** to build a custom GPT).
2. Find the **instructions** box (in a project, "Add instructions"; in the GPT builder, the **Configure** tab's Instructions field). Paste the full prompt from [`SYSTEM_PROMPT.md`](SYSTEM_PROMPT.md), the text between the two rules. If the box has a character limit the full prompt does not fit, use the shorter version at the foot of that file.
3. Add the seventeen JSON files from `knowledge-graph/` as **files** (project) or **knowledge** (GPT). Custom GPTs accept a limited number of knowledge files; seventeen is within it at the time of writing, but if yours refuses, start with the eleven listed in the [companion README](README.md).
4. Open a chat inside the project or GPT and run the limits check from the README. Then tell it a dream.

## Notes

- ChatGPT's memory settings decide whether the companion remembers dreams across chats. Check **Settings, Personalization** and choose what you are comfortable with.
- If you build a custom GPT and consider sharing it, the data license applies: CC BY-NC-SA 4.0, with attribution to Andrew Christison and foreverju.ng. A free, attributed GPT is fine. A paid one is not, without permission.
- The files are JSON. ChatGPT reads them as text; no conversion needed.
