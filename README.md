# Dowerks

Dowerks is a personal productivity system used through a file-capable AI agent. It keeps the thread of things you care about so you can return without rebuilding the context.

## Start

Open this folder in an agent that can read and write local files. Describe something you want to remember or work on, even an incomplete thought:

> I need to fix the door. It catches sometimes, but I haven't looked into why.

The agent saves context, asks useful questions, and helps research, draft, organize, or develop a next step. It asks for your judgment, information, or physical participation where needed.

Return to the same folder to continue: “Let's look at the door again,” or “I've got twenty minutes. Help me choose something to work on.” You can defer or release issues; remembering something does not make it a commitment.

You initiate engagement. Dowerks does not run between sessions or send proactive reminders. You can also ask it to change how it helps you and save that behavior for future interactions.

## How it is kept

Each issue lives in a Markdown document under `issues/`, shaped to fit the work.

[AGENTS.md](AGENTS.md) and the [issue skill](.agents/skills/dowerks-issues/SKILL.md) guide the agent. If it does not load them automatically, ask it to read both.

Keep this folder available and backed up. Git does not save changes automatically, and issue documents are not ignored by default.
