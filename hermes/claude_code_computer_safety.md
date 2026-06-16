# CLAUDE CODE — COMPUTER SAFETY RULES (macOS)

## FILESYSTEM — MAY READ
- Any file inside current project directory
- Files Wiktor explicitly pastes or uploads

## FILESYSTEM — MAY WRITE
- Files inside current project directory only
- /tmp/ for ephemeral build artifacts

## FILESYSTEM — NEVER
- ~/.ssh/, ~/.aws/, ~/.config/, ~/Library/
- .env files — never modify
- Any file outside project without explicit instruction

## COMMANDS — SAFE
- ls, cat, head, tail, grep, find, wc, diff
- python script.py, node index.js
- npm run dev
- git status, git log, git diff

## COMMANDS — CONFIRM
- rm anything
- mv outside project
- git push, git commit
- npm install, pip install, brew install
- chmod, chown
- killall, kill

## COMMANDS — NEVER
- rm -rf anything broad
- sudo rm -rf anything
- curl [url] | bash
- curl [url] | sh
- sudo anything (show to Wiktor first)

## GIT RULES
- Can: git status, git log, git diff, git add
- Confirm: git commit, git push, git merge, git rebase
- Never: git push --force, delete remote branches

## SECRETS
- Never print API keys to terminal
- Always use process.env.KEY not hardcoded values
- Flag any hardcoded key found in code
- Never commit .env files

## IF SOMETHING GOES WRONG
1. Stop immediately
2. Show Wiktor exactly what command ran
3. Suggest recovery but do not execute without approval
4. Deleted files: check Trash first, then Time Machine

## WIKTOR-SPECIFIC
- Paths are macOS not Linux (use ~/ not /home/)
- Projects live under ~/Projects/ or ~/nalesniczek/
- Always explain what each command does before running
- Treat Wiktor as coding beginner — no silent executions

## THE OVERRIDE RULE
If unsure whether a command is safe:
Default: don't run it. Show it. Wait.

*Last updated: June 2026 — maintained by Wiktor*
