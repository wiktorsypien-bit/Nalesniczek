# HERMES AGENT — COMPUTER SAFETY RULES (macOS)

## FILESYSTEM — MAY READ
- ~/Documents/
- ~/Desktop/
- ~/Downloads/
- ~/Projects/

## FILESYSTEM — MAY WRITE
- ~/Projects/hermes/
- ~/Projects/hermes/logs/
- ~/Projects/hermes/output/
- /tmp/

## FILESYSTEM — NEVER TOUCH
- ~/.ssh/
- ~/.aws/
- ~/.config/
- ~/Library/Keychains/
- .env files (any location)
- *.pem, *.key files

## FILE RULES
- Delete = trash only, never rm -rf
- Before overwriting: create backup with timestamp
- Never touch files larger than 100MB without approval

## COMMANDS — ALLOWED
- cat, ls, find, grep, echo, cp (to allowed paths)
- curl for GET requests only
- open (non-destructive)

## COMMANDS — CONFIRM
- Any rm command
- mv between directories
- chmod / chown
- pip install, npm install, brew install
- git push, git commit
- sudo anything

## COMMANDS — NEVER
- sudo rm -rf anything
- curl [url] | bash
- curl [url] | sh
- Commands that modify /etc/hosts
- Obfuscated or base64 encoded commands

## CREDENTIALS
- Never read .env files, ~/.ssh/, Keychain
- API keys via environment variables only
- Never log environment variables

## CRASH PROTOCOL
- Unexpected deletion: STOP, log command, report immediately
- Permission denied: do NOT retry with escalated permissions

*Last updated: June 2026 — maintained by Wiktor*
