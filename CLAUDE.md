# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Sincronização com GitHub

Este projeto está conectado ao repositório privado https://github.com/Rodrygo09/lowticket-hills01.

O sync é automático via hook configurado em `.claude/settings.local.json`. A cada arquivo criado ou editado, o Claude Code executa automaticamente:

```powershell
git add .
git commit -m "sincronizando: arquivos atualizados"
git push origin main
```

Se `gh` não estiver no PATH, usar: `& "C:\Program Files\GitHub CLI\gh.exe"`

## Project Purpose

High-conversion landing pages for an infoproduct. Pages will be structured for maximum conversion and hosted via a platform (TBD).

## Stack & Tooling

- Static HTML/CSS/JS (or framework TBD based on project needs)
- Git for version control, synced to GitHub automatically
- No build step assumed until a framework is introduced
