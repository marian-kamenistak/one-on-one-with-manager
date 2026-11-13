# One-on-One with Manager

by [Marian Kamenistak](https://www.marian.coach/), engineering-leadership mentor

**Tell it what you want from your manager. Get one page for your next 1:1: the opening line, the one ask, the evidence, the pushback you will hear and your answer, and the note to send afterwards.**

Most people I mentor have done the next-level job for months before they ask for it. The growth talk moves "to next time", the 1:1 fills up with status updates, and the ask is not said in a way the manager can act on. The 1:1 belongs to you. This skill helps you walk in with one ask and walk out with a decision, a date, or the gap in writing.

## What you get

- **One ask.** If you bring five topics, the skill picks the one that needs your manager's decision and parks the rest, with where each one goes.
- **An opening line**, word for word: the topic, the ask, and what your manager gets out of it.
- **Your ask rated on six levels**, from Problem to Done: once as you brought it, once as the page says it, and the sentence that moves it higher.
- **The likely pushback**, two lines your manager is likely to say, and an answer for each in your words. Plus what to ask for when the answer is "not now".
- **A timed agenda** for your slot. The ask comes first and status comes last.
- **Two short notes:** a pre-read to send the day before, and a follow-up to send the same day.
- **A short mode for managers** preparing a 1:1 with one of their reports.

It does not invent a number or a quote for you. Where a fact is missing, the page leaves `[a bracket]` and tells you how to fill it, usually in ten minutes.

## The six levels of an ask

| Level | Name | Sounds like |
|---|---|---|
| 1 | Problem | "I feel underpaid." |
| 2 | Solution | "I want the tech lead title." |
| 3 | Data | "I have run planning and reviews for 8 months." |
| 4 | Metric | "By the March cycle, the squad ships without me in every review." |
| 5 | Return | "You get one person who owns delivery while you run the reorg." |
| 6 | Done | "I have done this job for 8 months. Incidents went from 9 to 3." |

A problem alone gets sympathy. Data, a proposal and what your manager gets back get a decision.

## Example

An invented case: a senior backend engineer at a 200-person fintech who has led the payments squad for eight months without the title. The page starts like this.

```
# Your 1:1 with your manager, Thursday · 30 min

The ask: Agree that I move to payments tech lead in the [cycle] cycle,
and set a date to decide pay, with what is missing written down.
Ask strength: level 3 of 6 as you brought it, Data
→ level 6 with this page, Done: the job is already done, the number
shows it, and the opening line says what she gets.

Opening line
"I'd like to use today for the growth talk we moved. I've led payments
for 8 months and cut incidents from 9 to 3 a quarter. Can we make me tech
lead in [cycle], so you have one owner for payments during the reorg?"

Parked
- Ledger API ownership with the cards squad → talk to their lead first,
  then bring it as its own ask.
```

## Install

```
npx skills add marian-kamenistak/one-on-one-with-manager
```

Or copy this folder into `~/.claude/skills/`.

## Use

```
/one-on-one-with-manager
```

Or just say "I have a 1:1 with my manager on Thursday and I want to ask for the tech lead role." A long message with your numbers gets a page right away. A short one gets five quick questions first.

## Rules it keeps

- **One ask per 1:1.** A second hard topic gets its own slot.
- **No surprises.** A big ask reaches your manager in writing the day before.
- **Written the same day.** Decisions, owners and dates go in the follow-up note.
- **Your facts only.** Numbers, dates and quotes come from you or stay in brackets.

## Where it comes from

Distilled from 3,662 1:1 leadership sessions with engineering leaders since 2019. The agenda order, the six levels and the questions managers ask before they say yes come from the playbook I use with mentees. The six levels are written up in [why your manager isn't listening to you](https://www.marian.coach/blog/how-to-influence-my-manager/).

Version 1.0 (13 Nov 2026). MIT license.
