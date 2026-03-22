### Claude Code 101
My learnings with Claude Code

Asked claude to open the html file in the browser by running this command `start tictactoe.html` and this created a .claude folder with a json file.

### Commands
- `/help` -> see all available shortcuts in generals tab and see commands available in claude code
- `/init` -> creates a Claude.MD file to create persitent memory of the codebase so that it can review it during each session.
- `Something` I asked Claude Code to do -> "Update the @CLAUDE.md file to indicate that as you do work you need to commit things to Git and push them to GitHub regularly with clean commit messages so we never lose the status or work that we have done."
- `/tasks` -> Running a web server is blocking which claude will detect and put on a background tasks which you can then see via -> `/tasks`
- `/agents` -> Allows you to create different agents for different tasks

### Modes
- Ask mode -> The default mode (Terminal will show uestion mark symbol)
- Code mode -> Code by default without asking for permission (Terminal will say accept edits on)
- Planning Mode -> Creates a plan that claude will follow (Terminal will say plan mode on)
Press shift + tab to change mode


### Shortcuts
- Press esc twice will clear the line
- option/alt + enter to create line break
- ctrl + o to see it thinking
- Command + B to run in background mode

### Skills
- Skills live in the .claude/skills folder and it can include things like your pr review style, design style, commit style etc.

### Other Tips
- In your Claude.MD, include a build and validation step and then get it to build the app by prompting
- In an empty input, if you press esc twice, it brings up previous inpouts allowing you to rewind
- You can add screenshots to the context
- `/clear` clears the context
- `/context` gives you current context that claude code is operating own -> shows you all the MCPs etc which are chewing your tokens
- `/compact` summarises the session
- `/resume` gives you the old context. Used when you accidentally nuke a session.
- `/mcp` shows you mcps configured. Does blow up token usage
- Add a critical rules section -> e.g., "Never do X" but "Always do Y" and give code snippets or get it to add code snippets and get claude to update the rule

### Daily Workflow
- Start in plan mode and never accept the first answers it gives me
- Fresh context is best context that's why you start with plan mode to build up the context
- Persist before ending sessions -> tell it to save to Claude MD
- Add a todos section to Claude.MD
- Press escape to interrupt it and don't be afraid to do that

### Composable Framework
- Skills:
    Recurring Workflows -> e.g., Fetch hacker news and save summary -> can then save it as a skill

