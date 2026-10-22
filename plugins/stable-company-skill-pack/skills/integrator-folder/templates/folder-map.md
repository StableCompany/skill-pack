> CLAUDE.md: how this folder works. Your assistant reads it first in every session. Keep it short. Edit it any time.

# My Integrator folder

This folder holds what is true about my company and my week, written down once, so your assistant never starts from zero. Read this file first. Then read only what the job needs, using the table below.

## What lives here
- `company.md`: the company snapshot. Team and seats, values, this quarter's priorities, scorecard, meeting rhythm, brand. Only the integrator-folder skill changes it, except the Brand section, which a skill may fill after my yes.
- Our tool (named in `company.md`) is the record for priorities, to-dos and numbers. Read it through a connector if one is on, or ask me for a paste. Never write to it.
- `how-we-run-meetings.md`: how each of our meetings really runs. A skill adds to it the first time it preps that meeting, after my yes.
- `voice-profile.md`: how I write. Only the voice-profile skill writes it.
- `todos.md` and `issues.md`: running lists. The line format is at the top of each file.
- Each folder has a `CONTEXT.md`. Read it before you write in that folder.

## Jobs
| Job | Skill | Read | Skip | Save to |
|---|---|---|---|---|
| Set up or update the snapshot | integrator-folder | company.md | everything else | company.md |
| Learn how I write | voice-profile | voice-profile.md | everything else | voice-profile.md |
| Prep the weekly meeting | weekly-meeting-prep | company.md, how-we-run-meetings.md, todos.md, issues.md, the newest meetings/*-weekly-prep.md, notes since then | people/, clarity-breaks/ | meetings/ |
| File notes from a meeting | meeting-to-actions | company.md, todos.md, issues.md, people files for who was there | clarity-breaks/, quarterly/ | meetings/, todos.md, issues.md, people/ |
| Prep or log a one-on-one | one-on-one | that person's file, company.md, how-we-run-meetings.md, todos.md, notes since the last one | other people's files, clarity-breaks/ | people/ |
| Check in on this quarter's priorities | rock-check-in | company.md, your tool (read only, or one paste), the newest meetings/*-rock-check-in.md and *-weekly-prep.md, notes since then, todos.md | clarity-breaks/, visionary/ | messages/, meetings/, issues.md, todos.md |
| Solve one issue to its root cause | issue-solver | issues.md, the meetings/ notes where it came up, company.md, how-we-run-meetings.md | people/, clarity-breaks/, visionary/ | meetings/, issues.md, todos.md |
| Same-page meeting with my Visionary | same-page-prep | visionary/, company.md, how-we-run-meetings.md, issues.md, recent prep sheets | people/, clarity-breaks/ | visionary/ |
| Clarity break | clarity-break | company.md, how-we-run-meetings.md, my last break, issues.md, visionary/open-items.md | meetings/ | clarity-breaks/ |
| Quarterly planning prep | quarterly-prep | company.md, how-we-run-meetings.md, issues.md, this quarter's meeting notes | people/, clarity-breaks/ | quarterly/ |
| Write or check this quarter's priorities | rock-writer | the quarter's rock-ideas.md and rock-review.md, company.md, how-we-run-meetings.md, annual/<year>/year-calendar.md, your tool (read only) | people/, clarity-breaks/ | quarterly/ |
| Prep for annual planning | annual-planning-prep | company.md, how-we-run-meetings.md, quarterly/, issues.md, the year's meetings/ notes, your tool (read only) | people/, clarity-breaks/, visionary/ | annual/ |
| Map a process | process-map | company.md, that process's folder | everything else | processes/ |
| Write an SOP or checklist | process-doc | that process's map.md, voice-profile.md | other processes | processes/ |
| Tell people about a decision | cascade | company.md, voice-profile.md, people files for anyone named | clarity-breaks/ | messages/ |
| Not sure which skill fits | pack-guide | nothing; it only checks that company.md exists | everything | nothing |
| A quick question ("what do I owe my Visionary?") | none | the one file that holds the answer | everything else | nothing; name the file you used |

## Rules for every job
1. Never invent. No made-up people, numbers, dates, owners or quotes. Unknown stays a question in the file.
2. Show me first. Before you file anything, save over a file, or change a file another skill owns, show me what will change and wait for my yes.
3. Drafts only. Never send, post, or change anything outside this folder.
4. Lists and logs grow. Add new lines. Change a line only to move it to Done or Solved, or to give a to-do the new date my notes say, and only after my yes. Never rewrite past entries.
5. clarity-breaks/ is private. My candid words never leave it. An item goes out only as an issue or a neutral question, after my yes.
6. Use our words for our own system: what we call our priorities, seats and meetings. Plain words and short sentences everywhere.
7. If the priorities in company.md are from a past quarter, say so before you use them.

## How files are named
- Dates first, as YYYY-MM-DD: `meetings/2026-11-02-weekly-prep.md`.
- People: `people/first-last.md`, lowercase, with a hyphen.
- Every file your assistant writes starts with one line: what it is, the date, and which skill wrote it.

## My own rules
Add your own lines here. They win over the rules above, except rules 1 and 3.
