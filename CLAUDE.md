# Project Rules

## Version Control Setup
- This project follows the conventional version control setup from the global CLAUDE.md.
- Project root: this directory.
- Git and gh user: JesserHamdaoui.
- Baseline committed: yes, `chore(init): add project baseline` on `main`.
- Remote: https://github.com/JesserHamdaoui/data-science-project (public).

## Secret Scan
- The gitleaks pre-commit hook is installed, pinned to `rev: v8.30.1`, config in `.pre-commit-config.yaml`.
- Each fresh clone must run `pre-commit install`, because the hook is not committed.
- Never skip it: no `SKIP=` and no `--no-verify`.
- No baseline file.

## Notes
