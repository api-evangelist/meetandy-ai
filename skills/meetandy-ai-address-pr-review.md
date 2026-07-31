---
name: address-pr-review
description: Triage and respond to PR review feedback — judge whether each comment has merit, fix the valid ones, reply to the rest, and check CI. Use when you've received review comments on a pull request and want to work through them before pushing.
---

# Address PR review

We just received PR review comments for this PR. Help me work through them.

1. For each piece of feedback, check whether it has merit.
   - If it does, fix it.
   - Otherwise, leave a brief reply to the review comment explaining why.
2. Leave the reply comments **before** pushing the fixes.
3. Check the **main comments**, not just inline comments.
4. Check CI in case there are test or lint errors, and fix them properly.
5. For existing legacy issues not directly related to our changes but pointed out
   by the reviewers, be constructive — treat it as a chance to improve and leave it
   better than you found it.

## Guardrails

- Do **not** write "#1" (or similar) in comments — GitHub may auto-link it to an
  unrelated issue. Reword to avoid the `#<number>` pattern.
- **Never tag the reviewer if it's a bot.**
- If you're on the fence about whether a piece of feedback has merit — or about a
  refactor suggestion — stop and ask me to decide.

