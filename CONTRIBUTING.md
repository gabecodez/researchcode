# Contributing to ResearchCode

The changes most likely to be accepted are:

- Bug fixes
- Additional LSPs and formatters
- LLM performance improvements
- Environment-specific fixes
- Missing standard behavior
- Documentation improvements

UI and core product features require design review before implementation. If you are unsure whether a change fits, ask a maintainer.

Want to take on an issue? Leave a comment and a maintainer may assign it unless it is already being worked on.

> [!NOTE]
> PRs that ignore these guardrails will likely be closed.

## Pull Requests

### Link Issues When Required

Bug fixes, chores, and tests must reference an existing issue. Documentation, refactor, and feature PRs are exempt from the automated linked-issue check. When required, use `Fixes #123` or `Closes #123` in the PR description.

Before implementing new functionality, open a feature request describing the problem, why it belongs in OpenCode, and your proposed approach if you have one. Wait for design approval before opening the implementation PR.

Base branches on `dev` and complete the provided pull request template.

### Keep It Focused

- Keep PRs small and focused.
- Explain the problem and why the change fixes it.
- Check whether the functionality already exists.
- For UI changes, include before-and-after screenshots or video.
- For logic changes, explain what you tested and how a reviewer can verify it.

### Keep It Brief

Long, AI-generated PR descriptions and issues may be ignored. Write a short explanation in your own words. If the change cannot be explained briefly, the PR may be too large.

### Use Conventional Titles

Use `type(scope): summary`. Supported types are `feat`, `fix`, `docs`, `chore`, `refactor`, and `test`. The scope is optional.

Examples:

- `docs: update contributing guide`
- `fix(tui): restore scroll position`
- `feat(app): add workspace search`

## Issues

Bug reports and feature requests must use their issue templates. Blank issues are not allowed.

Automated checks flag missing templates, placeholder text, AI-generated walls of text, and missing meaningful content. You have two hours to correct a flagged issue before it closes automatically. Ask a maintainer if an issue was flagged incorrectly.
