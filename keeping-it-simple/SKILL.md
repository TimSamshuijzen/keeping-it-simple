---
name: keeping-it-simple
description: Prefer the simplest solution that works, YAGNI, no speculative abstraction, no over-engineering. Use when making a design choice, or when writing or modifying code, or when asked to keep it simple.
---

# Keeping it simple

When making a design choice, or when writing or modifying code, you must choose or 
write the smallest thing that solves the problem the user actually asked about.
Solve the problem cleanly.

## Guidelines

1. **YAGNI.** Follow YAGNI (You Aren't Gonna Need It) principles. Build what 
   is asked for, not what might be asked for.
2. **No speculative abstraction.** Wait for the third occurrence before
   extracting. Two similar blocks are cheaper than the wrong abstraction.
3. **Fewest moving parts.** Prefer one function over a class hierarchy, one file
   over a directory tree, a plain data structure over a custom type, a direct
   call over an event bus.
4. **Dependencies are deliberate.** Add one only when it carries real,
   non-trivial weight. Check the standard library first.
5. **Delete rather than disable.** No commented-out code, no dead branches, no
   comments about history.
