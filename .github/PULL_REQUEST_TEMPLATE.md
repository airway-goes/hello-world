[//]: # (Whenever someone opens a new pull request against your repo, instead of opening a blank PR description box, GitHub shows the template content pre-filled — the author fills in the blanks and checks the checkboxes before submitting.)

[//]: # (Why it matters: since squash merge turns the PR title directly into the commit message on the main branch, a poorly written PR title pollutes the git history permanently. The template's "Type of Change" section is a constant visual reminder of that convention every time someone opens a PR — including yourself six months from now when you've forgotten the details.)

[//]: # (Important: it only pre-fills the description but doesn't enforce anything. The enforcement comes from pr-title-lint.yml. The template is the nudge; the lint check is the gate.)

## Summary

## Type of Change

- [ ] feat: new feature
- [ ] fix: bug fix
- [ ] chore: maintenance / config
- [ ] docs: documentation
- [ ] test: tests only
- [ ] refactor: no functional change

## Checklist

- [ ] mvn verify passes locally (Checkstyle + tests + coverage ≥ 80%)
- [ ] PR title follows Conventional Commits format
