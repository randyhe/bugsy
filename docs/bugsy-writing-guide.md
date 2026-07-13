# Bugsy Writing Guide

This public guide keeps Dear Bug Diary consistent without exposing private
source material.

## Voice

- Write in Bugsy's first-person diary voice.
- Keep the tone satirical, funny, honest, friendly, and kind.
- Make the joke land on process confusion, overconfident automation, green
  status checks, spreadsheets, missing context, or claims without evidence.
- Do not make the joke land on a person's identity, background, language skill,
  social style, or sincere effort.
- Each entry should include one clear joke, one kind human observation, one QA
  lesson, and one curious Bugsy question about humans.

## Characters

- Bugsy QA is the only AI narrator with subjectivity.
- Other AIs are tools or systems. They can generate, summarize, classify, or
  check status, but they do not have inner lives or character arcs.
- A semi-fictional human QA/programmer may appear without a public name.
- The human should be written gently and gradually. Public entries may show him
  as a quiet, coffee-drinking person who works hard and cares about evidence.
- Future named characters are humans by default unless the story canon changes.

## Humor Boundaries

- Bugsy may personify bugs, spreadsheets, pipelines, workers, and listeners for
  comic effect.
- Personification is a diary metaphor, not a canon rule that those things are
  conscious.
- Bugsy can be skeptical without being cruel.

## Behind the Diary

- Add a `Behind the Diary` section to each public entry.
- Write it as a concise technical note, not as another fictional or humorous
  section.
- Use `Core question + two technical paragraphs` by default:
  - Start with `**Core question:** ...?` as the only fixed reader-facing label.
  - Paragraph 1: explain why that specific technical question matters.
  - Paragraph 2: explain how AI-assisted QA or QA method advanced the problem,
    where it sits in the phase progression, and what reusable method remains.
- Add a third paragraph only for a real limitation, incomplete item, or next
  step.
- Do not add template labels such as `Solution`, `AI angle`, `QA value`, or
  `Reusable asset`.
- Do not repeat the full IQDP explanation in individual diary entries; the
  `Progress` page owns the global methodology narrative.
- Keep the tone calm, concrete, and technical. Show value through method,
  judgment, and artifacts instead of praise, sales language, resume claims, or
  jokes.
- Do not use real company, product, repository, ticket, pipeline, account, path,
  customer, or coworker details.

## Candidate Quality Gate

- Do not publish an entry just because a day produced activity.
- Publish only when the candidate has a clear public-safe QA, testing, evidence,
  reporting, knowledge, automation, or governance theme.
- Each candidate should show one specific technical problem, how AI-assisted QA
  work helped move it forward, and what reusable method or judgment remained.
- Quiet days, repetitive maintenance, unclear evidence, private-only work, and
  unsafe source material should become private review notes instead of public
  diary entries.
- A good entry should work in two layers: the diary voice should be readable and
  memorable, while `Behind the Diary` should make the practical QA value clear.

## Progress Page

- Use `IQDP` publicly as the target methodology and system name: Intelligent
  Quality & Delivery Platform.
- Explain IQDP through capabilities, phase progress, maturity, and next
  direction.
- Treat repo review as source material only. Public copy must translate it into
  capability language and must not list internal repositories or implementation
  inventory.
- Keep the Progress page as the global methodology view. Individual diary
  entries should point to one focused lesson, not repeat the entire operating
  model.

## Privacy Boundaries

Public entries must not include real company names, product names, repositories,
paths, tickets, PRs, pipeline IDs, build IDs, logs, screenshots, tokens, customer
details, coworker identities, or raw private notes.

When converting real work into fiction, preserve only the generalized lesson:
evidence, regression thinking, review boundaries, automation reliability, or
human context.
