# /powerup Video — Read-Aloud Script
# Voice: Julio Casal
# Instructions: Read naturally. Pause briefly (1-2 seconds) between sections.
# The pauses tell Clio where the visual transitions go.

---

## SECTION 1 — INTRO (read over the welcome screen)

Claude Code just dropped something really cool in their latest update, and I haven't seen anyone talking about it yet.

It's called powerup, and it's basically an interactive tutorial system, with animated demos, built right into the terminal.

Let me show you.

[PAUSE]

---

## SECTION 2 — MENU (read as the powerup list appears)

You type slash powerup, and you get this menu with ten lessons. Each one covers a feature that honestly, most developers never even find.

Let's go through the ones I think matter the most.

Starting with this first one — Talk to your codebase.

[PAUSE]

---

## SECTION 3 — PU1: TALK TO YOUR CODEBASE (read while the animated demo plays)

This one is about using the at symbol to reference files directly in your prompt. You get a search box, it finds the file, reads it, and Claude can actually answer with full context.

No more copying and pasting code into the prompt. And you can even point to specific line numbers.

[PAUSE]

---

## SECTION 4 — PU2: STEER WITH MODES (read as we move to the next powerup)

Next one, Steer with modes.

This is one of those things that completely changes how you use Claude Code day to day.

You hit Shift Tab and you cycle through the different permission modes. You've got plan mode, where Claude thinks before doing anything. And then there's auto mode, which uses an AI classifier to figure out which operations are safe and just approves them automatically.

You're not sitting there clicking allow on every file read anymore.

[PAUSE]

---

## SECTION 5 — PU3: UNDO ANYTHING (read as we move to the next)

Alright, this next one — Undo anything.

Honestly, this one alone makes the update worth it.

Claude checkpoints every file before it makes a change. If something goes wrong, you just double tap Escape, it opens rewind, and you can roll back to any previous state. Code, terminal, everything goes back.

[PAUSE]

---

## SECTION 6 — PU5: TEACH CLAUDE YOUR RULES (read as we move to the next)

Now this one — Teach Claude your rules.

This is where Claude Code starts to feel like it actually knows your project.

You drop a CLAUDE.md file in your repo, and Claude reads it at the start of every session. You put your conventions in there, your test commands, your style preferences, whatever matters to your team.

And if you don't want to write it from scratch, you just run slash init and it generates one based on your existing codebase. Pretty nice.

[PAUSE]

---

## SECTION 7 — PU7: AUTOMATE YOUR WORKFLOW (read as we move to the next)

Automate your workflow. This one is about custom slash commands and hooks.

You save a prompt to the skills folder, and it becomes a slash command. You can have slash deploy, slash review, whatever your team needs.

And hooks let you run code before or after any tool call. For example, you could run your formatter after every file edit automatically.

[PAUSE]

---

## SECTION 8 — PU8: MULTIPLY YOURSELF + OUTRO (read over the last powerup)

And the last one I want to show you — Multiply yourself.

This is where it gets really interesting.

Claude can actually spin up copies of itself to work in parallel. You say, "use sub-agents to search these five directories," and it fans out. You can also define specialized agents in a folder — a test runner, a code reviewer, a docs writer — each with its own tools and instructions.

Go update to the latest version and type slash powerup. I think you'll be surprised by how many features are in there that you didn't even know about.

[END]

---

## RECORDING NOTES FOR CLIO

After Julio sends the recorded audio:
1. Detect silence gaps (>1s) → these are the [PAUSE] section boundaries
2. Measure each section duration
3. Record terminal with matching sleeps:
   - Section 1: welcome screen sits (duration of section 1 audio)
   - Section 2: type /powerup Enter at start, menu appears mid-section
   - Section 3: press Enter to open PU1 at start
   - Section 4: Escape → Down → Enter at start (transition to PU2)
   - Section 5: Escape → Down → Enter (PU3)
   - Section 6: Escape → Down → Down → Enter (skip to PU5)
   - Section 7: Escape → Down → Down → Enter (skip to PU7)
   - Section 8: Escape → Down → Enter (PU8), hold until audio ends
4. Render, compose, validate frame-by-frame
