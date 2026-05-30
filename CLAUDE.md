# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## GitHub Sync

This project is connected to a private GitHub repository at https://github.com/Rodrygo09/lowticket-hills01.

**Every change made to files in this project must be committed and pushed automatically.** After creating or modifying any file, run:

```powershell
Set-Location "C:\Users\USER\Desktop\LowTicket - Hills"
git add .
git commit -m "<concise description of what changed>"
git push origin main
```

Use `& "C:\Program Files\GitHub CLI\gh.exe"` if `gh` is not in PATH. Git itself is available directly via `git`.

## Project Purpose

High-conversion landing pages for an infoproduct. Pages will be structured for maximum conversion and hosted via a platform (TBD).

## Stack & Tooling

- Static HTML/CSS/JS (or framework TBD based on project needs)
- Git for version control, synced to GitHub automatically
- No build step assumed until a framework is introduced
