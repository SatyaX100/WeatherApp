# Contributing Guidelines
> 💡 Copilot tip: “Draft a bug report using our template for: login crash on Chrome 126 when form empty.”


## 3) Branching & commit style
- Branch from default: `feat/<scope>-<desc>` or `fix/<scope>-<desc>`.
- Use **Conventional Commits**:
- `feat(api): add pagination`
- `fix(search): handle special chars`
- `docs(readme): clarify setup`


> 💡 Copilot tip: “Generate a conventional commit message for this staged diff.”


## 4) Local setup & commands
- Requirements: Node 20 (adjust to your stack).
- Install: `npm ci`
- Build: `npm run build`
- Test: `npm test`
- Lint/format: `npm run lint` / `npm run format`
- Run locally: `npm run dev`


## 5) Coding standards
- Follow linter/formatter (CI enforces).
- Add/update tests with meaningful coverage.
- Keep functions focused; document non-obvious code.


> 💡 Copilot tip: “Write Jest tests for the new pagination util covering edge cases.”


## 6) Opening a Pull Request
- Use our PR template; keep the title concise and conventional.
- Link issues: `Closes #123`.
- Fill checklist:
- [ ] Tests added/updated
- [ ] Docs updated
- [ ] Screenshots for UI changes
- [ ] No breaking changes (or documented)


## 7) Reviews & approvals
- **CODEOWNERS** auto-requests reviewers.
- PRs require ≥1 approval (per branch rules).
- Address review comments with follow-up commits.


## 8) CI, quality gates, merge
- All required checks must pass (build, tests, lint, CodeQL).
- Squash merge by default; maintainers may edit commit title/body.


## 9) Documentation & releases
- Update docs/examples for user-facing changes.
- Add a CHANGELOG entry for significant changes.
- Maintainers cut releases; Copilot can draft notes.
