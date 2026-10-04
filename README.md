# Dowerks

Dowerks is a personal productivity system used through a file-capable AI agent. It keeps the thread of things you care about so you can return without rebuilding the context.

## Start

Open this folder in an agent that can read and write local files. Describe something you want to remember or work on, even an incomplete thought:

> I need to fix the door. It catches sometimes, but I haven't looked into why.

The agent saves rough context, connects relevant information, identifies what matters now, and helps research, draft, decide, or act. It asks for your judgment, information, or physical participation where needed. A useful partial result counts as progress: a decision made, materials acquired, or one part of a repair completed.

Return to the same folder to continue: “Let's look at the door again,” or “I've got twenty minutes. Help me choose something to work on.” You can defer or release issues; remembering something does not make it a commitment.

Each issue keeps enough current context to resume: where it stands, what has been established, and what remains unresolved. Its frontier is the evolving understanding of possible next steps and upcoming requirements; it does not require planning the whole issue in advance.

Work can be available to pursue, in flight, or completed. In flight means you've chosen it or clearly begun pursuing it. When helping choose work, the agent considers existing commitments and their demands on your time and attention, including how much it can handle for you.

You initiate engagement. Dowerks does not run between sessions or send proactive reminders. You can also ask it to change how it helps you and save that behavior for future interactions.

## How it is kept

Each issue lives in a Markdown document under `issues/`, shaped to fit the work.

[AGENTS.md](AGENTS.md) defines the shared domain language and general behavior; the [issue skill](.agents/skills/dowerks-issues/SKILL.md) guides work on issues. Domain names such as `FRONTIER` and `STATE` are written as constants in those instructions. If the agent does not load them automatically, ask it to read both.

Keep this folder available and backed up. Git does not save changes automatically, and issue documents are not ignored by default.
