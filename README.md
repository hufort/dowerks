# Dowerks

Dowerks is a small personal productivity system used through a file-capable AI agent. It keeps the thread of things you care about so you can return to them without rebuilding the context each time.

## Start

Open this folder in your preferred file-capable agent harness and describe something you want to remember or work on. There is no setup questionnaire. You can start with an incomplete thought:

> I need to fix the door. It catches sometimes, but I haven't looked into why.

The agent can save what is known, ask useful questions, and help develop a possible next step. You do not need to choose categories, assign a priority score, or write a plan first.

## Return to the work

Come back to the same folder and continue through conversation. For example:

- “Let's look at the door again. What do we know so far?”
- “I checked it: the top corner rubs against the frame.”
- “I've got twenty minutes. Help me choose something to work on.”
- “Put this aside until I can borrow the tools.”
- “I've decided this isn't worth pursuing. Keep the context, but let it go.”

The agent can research, draft, organize, and help reason through the work, then save relevant discoveries and decisions. It asks for your participation where your judgment, information, or physical action is needed. Remembering something does not automatically make it a commitment.

You initiate engagement. This version does not run between sessions or send proactive reminders.

## Make it your own

Tell the agent what works and what creates friction. You can ask it to change how Dowerks helps you and save that behavior for future interactions. An idea can also remain an idea until you want to pursue it.

## How it is kept

Each issue lives in a flexible Markdown document under `issues/`. The agent finds documents by listing and searching the folder. There is no index, required template, or fixed taxonomy.

`AGENTS.md` is the instruction entry point; `.agents/skills/dowerks-issues/SKILL.md` describes the working method. If your harness does not automatically load project instructions or discover local skills, ask the agent to read those files directly.

Your saved context lives in this folder. Keep it available for future sessions and include it in your normal backups. Git does not save new changes automatically; if you commit the folder, issue documents are included unless you choose to ignore them.
