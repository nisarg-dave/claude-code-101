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