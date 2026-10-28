# Repository Instructions

This repository packages the `digital-avatar-video` Codex skill.

## Structure

- Keep `SKILL.md` at the repository root so the repository can be installed as a skill directly.
- Put Codex UI metadata in `agents/openai.yaml`.
- Put detailed procedures and domain references in `references/` and link to them from `SKILL.md`.
- Keep examples generic. Never add API keys, personal avatar IDs, consent links, or private media URLs.

## Changes and Validation

- Keep changes scoped to the skill package and its documentation.
- Validate the skill with the Skill Creator `quick_validate.py` script when available.
- Do not commit secrets, generated videos, local journals, or account-specific state.
- Use a feature branch and a Conventional Commit. Do not push directly to `main`.
