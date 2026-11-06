# Working rules

## Version control
- Version control follows `docs/VERSION-CONTROL.md` (Beyond standard): work on a branch, push `wip/*` for unfinished work at the end of every session, never commit keys or signing files, and run `git config core.hooksPath .githooks` once per clone. Apple platform design follows Apple's Human Interface Guidelines; web UI is ReUI only.

## UI standard
- Any screen or component change follows `docs/ui-standard.md` (the Beyond UI standard, 30 rules: layout and touch checks plus hierarchy, contrast, proximity, alignment, progressive disclosure, feedback, error recovery, user control and intuitive patterns). Look at the result at 375px and 1280px, light and dark, before calling it done. Master copy: beyond-agent-hq `docs/ui-standard.md`.
