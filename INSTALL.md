# How to install the Handoff skill

A skill is a small folder with one instruction file inside. Claude loads it when you say the right words. You install it once.

The skill is the folder `skill/handoff/`. It has one file in it: `SKILL.md`.

Menus move around as Claude gets updates. If a button isn't where these steps say, look for the word "Skills" in Settings.

## Claude.ai (the website or the desktop app)

1. Zip the `handoff` folder. On a Mac, right-click the folder and choose Compress. On Windows, right-click, then Send to, then Compressed folder.
2. In Claude, open Settings.
3. Find Skills. It's usually under Capabilities. If you don't see it, check that code execution and file creation are turned on, and that your plan includes skills.
4. Choose to upload a skill and pick `handoff.zip`.
5. Make sure the skill is switched on.
6. Open a new chat and type: `check handoffs`. If Claude asks where your HANDOFFS.md file is, it's working.

## Claude Cowork

1. Open the Claude desktop app and go to Settings, then Skills.
2. Upload `handoff.zip` the same way as above, and switch it on.
3. Start a Cowork task in the folder that holds your shared brain. Type: `check handoffs`.

## Claude Code

1. Copy the `handoff` folder into the skills folder in your home directory. This command does it from inside the download folder and doesn't overwrite anything that's already there:

```
mkdir -p ~/.claude/skills && cp -Rn skill/handoff ~/.claude/skills/
```

2. To use it in only one project, copy it into that project's `.claude/skills/` folder instead.
3. Start a new Claude Code session and type: `check handoffs`.

## Using ChatGPT, or a plan with no skills?

You don't need the skill. Open `skill/handoff/SKILL.md`, copy everything under the top block, and paste it into your Project instructions. It works the same way.

## Check it worked

Say: `hand off to @Brain: this is a test`. Claude should write a short note in the right shape and add it to the top of your HANDOFFS.md. Then delete nothing. Just mark the test note DONE.
