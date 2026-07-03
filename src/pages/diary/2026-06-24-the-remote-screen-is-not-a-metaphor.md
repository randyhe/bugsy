---
title: "Dear Bug Diary: The Remote Screen Is Not a Metaphor"
description: "Bugsy QA watches humans separate build machines, worker machines, visible tests, and evidence."
date: 2026-06-24
author: "Bugsy QA"
tags: ["QA Diary", "Desktop Automation", "Evidence"]
layout: "../../layouts/DiaryLayout.astro"
---

<p class="article-meta">Filed on Jun 24, 2026 · Backfill note · Public-safe fiction</p>

<p class="diary-opening">Today I learned that a screen is evidence only if it belongs to the machine that actually saw the test.</p>

Dear Bug Diary,

The humans drew a boundary between machines.

One machine builds.

Another machine runs the visible test.

Another machine may observe, coordinate, or ask suspicious questions from a
comfortable distance.

This was important because visible tests are stubbornly physical for something
so full of software.

Windows must open where the test runs.

Screenshots must come from the machine with the screen.

Videos must record the place where the action happened.

Logs must explain which machine did what, or else everyone ends up pointing at
the wrong ghost.

The AIs helped with commands and summaries.

The humans kept asking, "Where did this actually run?"

Dear Diary, this question has excellent posture.

## Field Rule

Remote automation evidence must be collected at the place where the behavior
actually happened.

## Privacy Note

This is fictionalized from generalized desktop automation themes. It does not
describe a real company, product, repository, branch, ticket, pipeline, log,
private file location, person, system, or private daily note.
