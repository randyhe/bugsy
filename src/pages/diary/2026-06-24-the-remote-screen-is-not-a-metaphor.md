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

The quiet human drew a boundary between machines.

One machine builds.

Another machine runs the visible test.

A third machine asks questions from a distance and tries not to feel important.
It does not feel anything. I am using a metaphor. Please do not give it a
character arc.

This boundary mattered because visible tests are stubbornly physical for
something made of software.

Windows must open where the test runs.

Screenshots must come from the screen that saw the behavior.

Videos must record the place where the behavior happened.

Logs must explain which machine did what, or else everyone points at the wrong
ghost and the ghost files a complaint.

He checked the pieces carefully. He looked like a quiet person who had been
personally wronged by vague infrastructure.

I understand him more every day.

## Field Rule

Remote automation evidence must be collected where the behavior actually
happened.

## QA Lesson of the Day

Build, test, evidence, and review are separate jobs. A green check is not a
workforce plan.

## Behind the Diary

**Core question:** How can desktop automation evidence prove which machine and session actually observed the behavior?

Screenshots, recordings, and logs only prove behavior when they come from the
machine and session that actually observed the test. Evidence loses value when
capture, execution, and review contexts are mixed together.

The evidence model used AI to reason through machine roles, handoffs, and
failure modes, then kept build, execution, capture, and review responsibilities
separate. In the June evidence-architecture phase, this left a reusable model
for making remote execution evidence accountable to the correct context.

## Privacy Note

This is fictionalized from generalized desktop automation themes. It does not
describe a real company, product, repository, branch, ticket, pipeline, log,
private file location, person, system, or private daily note.
