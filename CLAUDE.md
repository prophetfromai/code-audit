# Code Audit

@/Users/qualitydrivensoftwareltd/git/claude.md/CLAUDE.md

## What This Project Is

A tool that analyses git history against work requests so business owners can verify whether outsourced development work was actually done — starting with freelance devs (Fiverr etc).

## Summary

The problem: when you hire a freelance developer (Fiverr, Upwork, etc), you often can't tell whether the work was actually done properly. You're paying for time or deliverables but have no easy way to verify what happened in the codebase against what was requested.

Code Audit bridges that gap. Point it at a git repo and a work brief (tickets, task descriptions, requirements), and it analyses the git history — commits, diffs, timing, file changes — against what was asked for. The output is a clear report for the business owner: was the work done? Was it done well? Does the activity match the claimed effort?

**MVP:** CLI or simple web tool. Input a repo + a description of requested work. Output a structured audit comparing git activity to the brief — flagging gaps, padding, or mismatches.

**Future direction:** A platform where developers build a verified track record. Freelancers who consistently deliver above expectation get ranked and surfaced. Think "approved workers" with audit-backed trust scores — turning code audit from a one-off check into an ongoing quality signal.

## Commands

```bash
npm run dev        # local dev server
npm run build      # production build
npm run deploy     # deploy to Firebase
```

## Monologue

`monologue.md` is this repo's rolling log of what people are thinking, asking about, and working on — captured in very few words. It gives any Claude session a sense of recent context before jumping in.

**Reading:** Scan `monologue.md` at the start of strategic or directional conversations.

**Writing:** When someone raises an idea, changes direction, or expresses intent — append a one-liner to the top of the Log section:
```
- [YYYY-MM-DD] Name: the gist in very few words — theme/feature
```

**Compaction:** The Log holds max ~20 entries. When full, distill the oldest entries into the Themes section (a few words each, merge with existing themes), then remove them from the Log. This keeps the file bounded forever.

Only capture signal: ideas, shifts in direction, decisions. Skip routine implementation chatter.

For the portfolio-level monologue (cross-product ideas and themes), see `/Users/qualitydrivensoftwareltd/git/director/monologue.md`.

## Project-Specific Rules

None yet — add rules as they emerge.
