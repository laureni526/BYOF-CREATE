# Repo State — snapshot as of October 16, 2026

*A description of what is in this repo and what changed in the last
week (Oct 9–16, 2026). It records what exists. It does not interpret
your stories, name patterns, or say anything is ready to promote. Open
items from this review are at the bottom of `open-questions.md`, under
"From the repo review (Oct 16)".*

## What this repo is right now

A **demo repo** (see the banner at the top of `README.md`) for the
"Build Your Council" session at She Leads AI CREATE 2026. It holds the
shared Build Your Own Foundry Full path plus your starting material and a
working council built from it. The README points people to the template
repo (`laureni526/build-your-own-foundry-full`) to build their own.

## Where it sits on the path

Inferred from the evidence, not decided for you: **Stage 1 (Feed the
System).** Stage 1's gate asks for 10–15 story cards from more than one
part of life, at least three monthly pattern checks, and a hunch
confirmed by new evidence. Today there are 6 story cards in 4 contexts,
one pattern hunch, and no recorded monthly pattern checks. No principle
exists, which fits Stage 1.

## Your own material (the Foundry)

| File | What it holds | Last changed |
|---|---|---|
| `north-star.md` | The north star question, plus a checklist of Stories 1–6 against it | Oct 16 (Story 6 added to checklist) |
| `stories.md` | 6 story cards: 1 "Don't tell me it's what I expected," 2 "Let people fail to succeed," 3 "Stealing the stretch work," 4 "My sister picks three," 5 "You can't scope what you don't understand yet," 6 "The Slack bot that worked and nobody used" | Oct 11 (Story 6 added) |
| `pattern-hunch.md` | One hunch (handing work back as a question), 4 stories, 3 contexts, status "a hunch, not a pattern" | Oct 11 (initial) |
| `open-questions.md` | 3 open questions, 1 hunch awaiting evidence, 2 parked "tempted to declare true" items | Oct 11 (initial), plus this review's additions |
| `mined-stories-slack-email-2026-09-16-to-2026-10-16.md` | 10 unreviewed story candidates, pattern-entry candidates, themes below threshold, question candidates, and a "Needs You Directly" list, mined from Slack, email and Granola | Oct 16 (new) |

The mined file says of itself that it is candidates, not Story Library
entries. Nothing in it has been moved into `stories.md`.

## The council (working demo)

- `.claude/skills/council/` is one skill: `SKILL.md` runner, five voices
  (advocate, critic, beneficiary, executor, long-view) in `voices/`, and
  `weaver.md` for synthesis. Changed Oct 11: it was seven separate
  skills, now one, and a request can name the whole council or a voice.
- The Critic is grounded in Story 6 first, with the Story 3 /
  doing-the-talking lens second (Oct 11).
- `expansions/council/` holds the starter kit (the pre-wired skill folder
  for others to copy) and the worked examples. The worked examples were
  swapped on Oct 11 to this demo council instead of the original
  Foundry-derived ones.

## Session materials (new this week, in the repo root)

- `proposal.md`: "Your Judgment Is the Source File," the 60-minute talk
  with live demo (Oct 11).
- `proposal-not-yet.md`: "Not Yet: Knowing When to Hold Someone Back," a
  90-minute workshop proposal. Drawn from Story 5 (Oct 16).
- `proposal-prep-partner.md`: "The Prep Partner," a six-week pilot
  proposal. Drawn from Story 6 and the Story 3 open question (Oct 16).
  The two proposals above are the fresh decisions for the live council
  run.
- `fallback-council-run.md`: a full-council run on the idea of opening
  the buildathon with a live demo, saved as the fallback if the live run
  fails (Oct 16).

## Changes by date

- **Oct 11** (PRs #1–#5): the demo Foundry created (north star, 5
  stories, hunch, open questions, council); `proposal.md` added; council
  consolidated into one skill; Story 6 added; Critic grounded in Story 6;
  worked examples swapped to the demo council; "Foundry" / "Lauren"
  references neutralized in `README.md`, the council expansion,
  `stage-1`, `stage-5`, and the mining README.
- **Oct 15–16** (PRs #6–#7): Story 6 added to the north-star checklist;
  fallback run; the two demo proposals; the mined candidates file.
- Path files (`stage-1` to `stage-5`, `templates.md`, `framework.md`,
  `participant-worksheet.md`, `worked-example.md`, `ai-thinking-partner.md`)
  were not changed apart from the small wording edits to `stage-1` and
  `stage-5` on Oct 11.
- Every commit except the initial one is authored by Claude sessions and
  merged by you through PRs.

## Not in the repo

No principles, no monthly pattern-check records, no practice documents,
no Stage 2+ files. Those aren't missing; the evidence for them isn't
here yet.
