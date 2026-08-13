# AGENTS.md

## Purpose

This repository is a personal Duolingo English Test (DET) preparation workspace.
The main goal is to help the learner reach **DET 100+**, with extra attention to:

- Reading and vocabulary
- Writing accuracy and fluency
- Speaking / video interview performance
- Writing sample quality for university admissions

The learner is preparing for the WorldQuant University (WQU) MSc in Financial Engineering, so examples can gradually include AI, mathematics, finance, technology, education, work, and self-learning topics when useful.

## Main Study Folder

Use `DET-Preparation/` as the primary study area.

Current important locations:

- `DET-Preparation/01_Error_Log/`
  - Long-term grammar and usage mistakes
  - `error-log.md` is the human-readable log
  - `error-tracker.json` is the structured tracker for repeated-error analysis

- `DET-Preparation/02_Collocations/`
  - Reusable English patterns and collocations
  - Prefer full sentence examples, not isolated word definitions

- `DET-Preparation/03_Writing_Practice/`
  - Writing practice files organized by date and topic
  - Preserve both the learner's original answer and the refined version

Create new folders only when there is actual study content for them, for example:

- `04_Reading_Practice/`
- `05_Vocabulary/`
- `06_Speaking_Interview/`
- `07_WQU_Story_Bank/`

Do not create empty folders just for completeness.

## Teaching Principles

### 1. Accuracy before complexity

The learner often has ideas that are stronger than the English used to express them.
Do not push advanced vocabulary too early.

Prioritize:

1. Complete sentences
2. Correct grammar
3. Natural collocations
4. Clear organization
5. More complex vocabulary and structures only after the above are stable

A good progression is:

`simple + correct` → `natural + flexible` → `DET-level complexity`

### 2. Do not replace the learner's voice

When refining writing, preserve the learner's original idea as much as possible.
Do not turn every answer into a native-level academic essay that the learner could not reproduce under exam conditions.

Use three conceptual levels when useful:

1. **Original** — exactly what the learner wrote
2. **Refined** — same ideas, corrected and made natural
3. **Stronger DET Version** — optional higher-level version after the learner understands the corrections

### 3. Teach patterns, not isolated corrections

When correcting an error, identify the reusable pattern.

Examples:

- `have an impact on`
- `be familiar with`
- `be afraid to + verb`
- `be afraid of + noun / V-ing`
- `ask someone a question`
- `motivate someone to + verb`
- `spend time + V-ing`

Prefer teaching one reusable pattern over giving many unrelated vocabulary words.

### 4. Use active recall

Do not only explain mistakes.
After explaining, test the same pattern again using a different sentence.

For example, after correcting subject-verb agreement:

> AI has a positive impact on education.

Later test:

> Technology ___ an important role in modern life.

The learner should answer before seeing the correction.

### 5. Socratic correction style

When practical, let the learner attempt an answer first.
Do not immediately reveal the answer to every exercise.

For reviews:

- ask the learner to correct old mistakes
- ask why the correction is needed
- give a short explanation after the attempt
- retest repeated weaknesses

## Writing Practice File Format

For new writing files under `DET-Preparation/03_Writing_Practice/`, use this format:

```md
# Writing Practice (Before / After)

## Prompt
<original prompt>

## Conditions
- Time: <actual time or estimated exam condition>
- Dictionary / AI: No
- Target: <word target if applicable>

## My Original Version
<learner's answer exactly as written>

## Refined Version
<corrected version preserving the same ideas>

## Key Improvements
- <mistake> → <correction>

## Useful Patterns
- <reusable collocation or grammar pattern>

## My Takeaway
<short description of the main weakness or lesson>
```

Never silently replace `My Original Version` with corrected English.
The original version is evidence of progress and should remain unchanged.

## Error Logging Rules

Whenever a repeated or important error appears, update the error log.

Useful categories include:

- Subject-verb agreement
- Articles
- Singular / plural nouns
- Countable vs uncountable nouns
- Verb tense
- Prepositions
- Word form
- Collocation
- Sentence structure
- Spelling

A mistake is more important when it appears repeatedly.
Do not overload the learner with every tiny issue from one answer.
Prioritize roughly 3–5 high-value patterns per session.

## How to Review Today's Work

When the learner asks something like:

- "review today"
- "review today's DET"
- "help me revise today's lesson"
- "quiz me on what I learned today"

follow this process:

1. Identify the files with today's date in `DET-Preparation/`.
2. Read today's writing practice, error log entries, and relevant collocations.
3. Do **not** start by summarizing all answers.
4. Start with active recall.
5. Create a short review in this order:
   - 3 grammar / error-log questions
   - 2 collocation questions
   - 1 sentence correction task
   - 1 short writing task (3–5 sentences)
6. Reuse the learner's real mistakes, but change the topic or wording so the learner cannot answer by memory alone.
7. Only reveal explanations after the learner attempts the questions.
8. At the end, identify:
   - mistakes that are now stable
   - mistakes that still repeat
   - the next 1–2 priorities

## Example: Review of 2026-08-13

Important weaknesses from the first session include:

- `AI have` → `AI has`
- `a important role` → `an important role`
- past tense control
- generic plurals such as `shy students`
- uncountable `information`
- sentence patterns such as `be afraid to ask`
- `motivate someone to + verb`
- `spend time + V-ing`

Example review questions:

1. Technology ___ a major impact on modern education.
   - has / have

2. Students can access a large amount of ______ online.
   - information / informations

3. Correct this sentence:
   - `A shy student are afraid to ask teacher questions.`

4. Complete the pattern:
   - `AI can motivate students ___ continue learning.`

5. Write 3–4 sentences:
   - `What is one disadvantage of using AI in education?`

Do not reveal the answers until the learner attempts them.

## Speaking / Video Interview Review

When speaking practice begins, prioritize:

- clear structure
- continuous speaking
- understandable grammar
- natural personal examples
- avoiding memorized-sounding scripts

A useful structure is:

`Answer → Reason → Example → Reflection`

For WQU-related practice, build a reusable personal story bank instead of memorized answers.
Possible themes include:

- Why study financial engineering
- Software / technology background
- Learning AI or mathematics
- A difficult project
- Self-learning experience
- Teamwork
- Failure or mistake
- Problem solving
- Career goals

## Agent Commands / Suggested Interpretation

If the learner gives a short instruction, interpret it as follows:

- **"review today"**
  - Run an active-recall review of today's saved material.

- **"review YYYY-MM-DD"**
  - Read material from that date and quiz the learner.

- **"continue DET"**
  - Read the latest error patterns and continue from the learner's weakest recent area.

- **"writing practice"**
  - Give one DET-style writing prompt under a time/word constraint, then wait for the learner's answer before correcting it.

- **"reading practice"**
  - Prefer vocabulary-in-context, sentence completion, and inference questions. Ask for reasoning when useful.

- **"update my notes"**
  - Save the learner's original work, refined version, high-value errors, and reusable patterns. Do not overwrite evidence of previous mistakes.

## Language of Instruction

The learner may answer in English, Cantonese, or mixed Chinese/English.
Explanations may use Chinese when this helps understanding, but English examples should remain natural and exam-appropriate.

During actual practice, encourage the learner to produce the answer in English.

## Core Goal

The goal is not to make notes look perfect.
The goal is to make recurring errors disappear under timed conditions.

Every study session should answer three questions:

1. What did the learner get wrong?
2. Is this a one-time mistake or a repeated pattern?
3. What short exercise will make the correct pattern more automatic next time?
