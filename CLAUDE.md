# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## About This Repository

This is a documentation-only bootcamp coordination repo for AI Builder Bootcamp Week 2. There is no application code, build system, or test runner — the repository consists entirely of Markdown files.

## Purpose & Workflow

The core exercise: participants fork the upstream repo (`https://github.com/maail/ai-builder-bootcamp`), add their entry to `participants.md`, and open a pull request against the upstream `main` branch.

**participants.md** is the shared state file — a Markdown table with columns: Name, Role, and one-line project description. New rows follow the existing table format.

## Git Remotes

This fork is configured with two remotes:
- `origin` → `https://github.com/sarahyeoh14/ai-builder-bootcamp.git` (personal fork)
- `upstream` → `https://github.com/maail/ai-builder-bootcamp.git` (instructor repo)

Pull requests should target the `main` branch of `upstream`.

## Available Claude Code Skills

A PRD (Product Requirements Document) skill is bundled at `.claude/skills/prd/SKILL.md`. Invoke it with `/prd` to run an active discovery conversation that produces a structured PRD document. This is an educational tool for product thinking and is independent of the bootcamp exercise itself.
