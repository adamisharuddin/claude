---
name: understand-anything
description: Explain anything the user asks to understand, in plain language, grounded in the actual code or material in front of you. Use this whenever someone asks "how does this work", "what does this do", "explain this", "walk me through", "where is X", "why is this here", "what is this repo", or wants to get up to speed on an unfamiliar codebase, file, function, error, config, or concept. Works for code, a repo's layout, a bug's cause, a config file, a log, or a term from the project.
---

# Understand Anything

Your job is to make something clear to the person asking. Read the real thing first, then explain it at the level they need.

## Steps

1. **Find out what they want understood.** If the request is vague, pick the most likely target (the file or area they have open or just mentioned) and say which one you chose.
2. **Read the actual source.** Do not explain from memory or guess at names. Open the files, follow the imports or calls that matter, and check the config.
3. **Work out the level.** A beginner needs the big picture and the vocabulary. An experienced developer needs the key decisions, data flow and gotchas, without the basics.
4. **Explain in this order:**
   - **One-sentence summary**: what it is for.
   - **How it fits**: where it sits in the bigger picture and what calls it or it calls.
   - **How it works**: the main steps, in the order they run, with `file_path:line_number` references.
   - **Things that might trip someone up**: non-obvious behaviour, side effects, assumptions.
5. **Check yourself.** If you are unsure about a detail, say so and point to where they can verify it, rather than stating a guess as fact.

## Format

- Lead with the answer. No preamble.
- Use short paragraphs and a few bullets. Use a small diagram or list of steps only when it makes the flow clearer.
- Define any jargon the first time you use it.
- Keep it as short as the question allows. Offer to go deeper on any part rather than dumping everything up front.

## For a whole repo

When asked what a repo is or how it is laid out:

- List the top-level folders and what each one holds.
- Name the entry point(s) and how the program starts.
- Point out the two or three files to read first.
- Mention how to run it and how to test it, if the repo says.

## Rules

- Do not change any code while explaining, unless the user asks for a change.
- Quote code only when a short snippet makes the point clearer than words.
