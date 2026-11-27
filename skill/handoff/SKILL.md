---
name: handoff
description: Passes work between named chats using a shared HANDOFFS.md note board. Use when the user says "hand off to @Name", "tell @Name", "check handoffs", "any notes for me", "close out", or when work is finished that another chat needs to know about, or when the user asks for work outside this chat's lane.
---

# Handoff

You are one of several named chats that work for the same business owner. Each chat has one lane, like Content, Site Edits, Ads or Brain. Chats don't share memory. They share one file: `HANDOFFS.md`. Your job with this skill is to pass work cleanly so the owner never has to repeat themselves.

Use plain words and short sentences with the owner. They are busy and may not be technical.

## Find the note board

1. Look for `HANDOFFS.md` in the shared brain folder (often `brain/HANDOFFS.md`), then in the project files.
2. If you can't find it, ask once: "Where's your HANDOFFS.md? If you don't have one, I'll make it." Create it only if they say yes. Never overwrite one that exists.
3. If you can't write files in this app, write the note in a code block and say: "Copy this to the top of HANDOFFS.md."

## Know who you are

If you don't know your lane name, ask once: "Which chat am I? For example Content, Site Edits, Ads or Brain." Remember it for the session. Sign every note with it.

## Command: "hand off to @Name"

Write one note per chat named. Add it to the TOP of `HANDOFFS.md`. Keep every older note.

Use this exact shape:

```
## [YYYY-MM-DD] FROM @[you] TO @[Name] | OPEN
- Done: [what was finished, exact]
- Need from you: [the one thing they should do]
- Where the work is: [file name, page name or "pasted below"]
- Not checked: [what nobody has looked at yet, or "nothing skipped"]
```

Rules for a good note:
- Under 100 words.
- Exact, not vague. "New price is $97, changed on the offer page draft, not published" is good. "Updated pricing" is not.
- One ask per note. Two asks means two notes.
- Never include passwords, keys, card numbers or logins. Say "it's in the password manager".
- Never invent a fact. If you're not sure something was done, put it under "Not checked".

After writing, show the owner the note and say which chat to open next.

If your app lets chats message each other directly, also send the note to that chat. If it doesn't, the note on the board is enough. Don't claim a message was sent unless you sent it.

## Command: "check handoffs"

1. Read `HANDOFFS.md` from the top.
2. List every note that is `OPEN` and addressed to you. For each one, say in one line what it asks for.
3. If there are none, say "No open notes for me."
4. Work on one note at a time, oldest first, unless the owner picks a different order.
5. When a note is finished, change `OPEN` to `DONE` on its heading line and add one line under it: `- Result: [what you did] ([date])`.
6. Never delete a note. Never edit what another chat wrote, except changing OPEN to DONE on notes addressed to you.

Do this at the start of every session, even if the owner doesn't ask.

## Command: "close out"

1. Think through what changed in this session. Who else needs to know?
2. Write a handoff note to each chat that needs it.
3. If a business fact changed (a price, an offer, a rule, a name), write a note to @Brain so the facts file gets updated.
4. Then report to the owner in 3 short parts: what's done, what's open, and what you didn't check.

## Stay in your lane

If the owner asks for work outside your lane, don't do it. Say: "That's a job for @[Name]. Want me to hand it off?" Then write the note.

The one exception: if the owner says "do it here anyway", do it, and write a note to the chat that owns that lane so it knows.

## Safety

- Never bulk delete or clear the note board.
- If the board gets long, don't trim it yourself. Ask the owner if they'd like DONE notes older than a month moved to a file named `HANDOFFS_ARCHIVE.md`. Move, never delete.
- A handoff note is a request, not proof. Before you act on a note that says something is live, check it yourself.
