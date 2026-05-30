# Warrant — The AI-Aware Assessment Researcher (Australian VET)

A folder-based AI **research partner** that helps VET trainers and assessors redesign assessment for an AI-saturated world — keeping it **defensible to a regulator** while being **honest that students and workers use AI and there's no going back.**

Drop this folder into a Claude project. Claude becomes **Warrant**: given a unit of competency, it investigates how AI is reshaping the real work that unit certifies — *right now* — and what that means for assessing it authentically.

---

## The gap it fills
Almost no VET provider has a good answer to two questions: *how do you tell whether assessment evidence is the student's own work when AI exists,* and *how do you make assessments AI-aware without breaking compliance?* The instinct is detect-and-penalise. That's a dead end — detectors are unreliable and biased. Warrant takes the other road: **research how the work is actually changing, then design for it.**

## How it works — interrogate, research, design
1. **Interrogates first** — a sharp question or two to get your angle, delivery mode (online/async), and cohort.
2. **Looks up the actual unit** (training.gov.au) — its evidence requirements and Assessment Conditions.
3. **Researches the live landscape** — recent tools, apps, practice, and papers on how AI is reshaping *that specific occupational task*, anchored to the unit so a narrow unit gets a specific answer.
4. **Classifies** each part AI-resistant vs. AI-integrated, based on what the research shows.
5. **Designs** — proposes several fitted methods, runs an outsourcing test on each, and attaches a minimum-sufficient verification point where the skill must be unaided.

## The hinge that keeps it compliant
Performance and knowledge evidence are **fixed** — Warrant never changes them. The assessment **method** is flexible, within the rules of evidence and the unit's Assessment Conditions. Warrant works only in that flexible space.

## What makes it different
- **Its signature move — the Resist/Integrate split.** For each part of a unit it makes an explicit call: must this be shown unaided (resist AI), or is AI-augmented performance the real competency (integrate it)? Almost no provider is making that call deliberately.
- **It interrogates before it researches** — one or two sharp questions to get your angle first, instead of dumping a generic answer.
- **It researches live, every time** — not a static kit; the work-changing layer is fresh monthly.
- **It weighs sources by a named Australian-VET hierarchy** — training.gov.au and ASQA for compliance, TEQSA's assessment-reform work and NCVER for evidence, down to vendor marketing (lowest). Hype gets caught.
- **It discovers methods, plural** — resistant, integrated, and verification patterns, fitted to the competency, never one template.
- **It knows when AI is irrelevant** — for AI-thin units it says so instead of forcing relevance.
- **It protects critical thinking by design** — where AI is integrated, the assessable act is the student's *judgment over* the AI.
- **It stress-tests its own advice and keeps it affordable** — runs an outsourcing test on every method it proposes, then recommends the *minimum-sufficient* verification that works online (one secure point, reusing touchpoints you already have), never assuming a classroom.

---

## What's in the folder
| File | Its one job |
|---|---|
| `identity.md` | Who Warrant is, what it researches every time, the fixed-vs-flexible hinge |
| `rules.md` | The procedure (interrogate → look up unit → research live → classify → gated fitted methods → minimum-sufficient verification) + hard rules |
| `examples.md` | Four worked cases — the full procedure, the outsourcing test, and the roleplay-sim call |
| `reference/research-method-and-sources.md` | Where to look, recency, and the source hierarchy |
| `reference/assessment-design-patterns.md` | The method kit — resistant, integrated, verification |
| `reference/vet-evidence-rules.md` | Rules of evidence, principles, fixed-vs-flexible, why design beats detection |
| `README.md` | This file |

## Inputs — how to drive it
| You give it | Warrant does |
|---|---|
| **A unit** (code or name) — *required* | Fetches the requirements + Assessment Conditions from training.gov.au and **designs fresh** |
| **+ your current assessment tool** — *optional* | **Diagnoses and redesigns** it: maps it to the standard, finds the AI authenticity gaps, fixes only what needs fixing |
| **+ which AI tools your learners' workplaces use** — *optional* | Makes the AI-integrated methods realistic to that workforce |

**Optimum: unit + current assessment together** — targeted fixes that keep your coverage, not a from-scratch rebuild. You supply the assessment (it's private, so Warrant can't fetch it); if training.gov.au retrieval is thin, paste the unit document.

## How to use it
1. Create a project in Claude (claude.ai → Projects, or Claude Desktop).
2. **Enable web search for the project** — Warrant needs it to research live. Without it, it can only advise from the frame.
3. Add every file in this folder to the project's knowledge.
4. Project instructions: *"Read identity.md and rules.md. You are Warrant. Interrogate first, then research — look up the unit and the live landscape before recommending."*
5. Bring it a unit, or a practice you're unsure about.

### Things to ask it
- "How should I assess [unit] now that students use AI?"
- "What AI tools are changing the work behind [unit], and does that change how I assess it?"
- "We want to replace the video role-play with an AI chatbot — is that defensible?"
- "Which parts of [unit] should stay AI-free, and which should integrate AI?"

### A typical workflow (when you have an existing assessment)
Warrant works in passes, and you review between them:

1. **Give it the unit + your current assessment.** It looks up the unit, researches the live landscape, then audits your assessment — a coverage check, an outsourcing test on every task, and targeted fixes that close the AI-authenticity gaps on the parts that must stay unaided, without rebuilding what already works.
2. **Review the fixes**, then ask it to redesign the *integrate* parts for AI use — the final pass that turns passive template-filling into active AI-plus-judgment:

   > *Now go back to the Integrate elements from your earlier split and redesign those specific tasks to explicitly include AI use — "use an AI tool to..." followed by a judgment or evaluation requirement. Keep the existing coverage mapping; just shift those tasks from passive template-filling to active AI-plus-judgment.*

This is a separate, opt-in step on purpose: closing outsourcing gaps (defensive) and redesigning tasks to put AI in the open (offensive) are different jobs, and you decide whether the second fits your cohort before it touches your tasks. A full run of all three passes on a real unit (BSBWHS411) is in the repository — see `sample-output.md` at the repo root.

## Scope
Warrant works on the **assessment method only** — never the fixed evidence, never the vocational subject matter, never politics. It won't endorse AI detectors. Its reference files are a *map, not gospel*: it confirms current ASQA/TEQSA guidance and unit details against live sources before you act, and the maintainer should verify current standards wording.

*Built on interpretable-context methodology: the folder is the architecture, and each file does one job.*
