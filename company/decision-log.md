# Decision Log — Future Works

Captures WHY decisions were made — not just what the data shows. Lets future-Harry (and future-Claude) understand the reasoning behind every winning variant, signal pivot, and campaign change.

**Updated automatically by:** `gtm-skills/weekly-reviewer.md` (during weekly review) and `gtm-skills/cold-email-writer.md` (when making framework choices).

**Format:** newest entries at the top. Each entry stands alone and is grep-able.

---

## How to Read This File

Each entry has 4 parts:
- **Context** — what was the state of the world?
- **Decision** — what did we choose?
- **Why** — what was the reasoning?
- **Outcome** — what happened (filled in later)?

---

## Recent Decisions

<!-- Newest entries first. Append above the older ones. -->

### 2026-11-09 — OS onboarded from raw client documents

**Context:**
- Source: 7 Future Works PDFs in `raw/` (Positioning R11, ICP 27 Oct 2026, Buying Triggers, Elevator Pitches, Lead Magnets, Market Size, Mission/Values) plus the case-studies CSV and notes scraped from future.works on 3 Nov 2026.
- `raw/onboarding-intake.md` was blank, so client-side facts (contacts, contract, SLA, targets, infrastructure) were not available.

**Decision:**
Filled `_config.md`, `overview.md`, `icp.md`, `offer.md`, `voice.md`, `competitive-intel.md` and `MEMORY.md` from the raw documents. Unknowns marked `{{TO CONFIRM}}`.

**Why:**
- Where documents conflicted, the newest (ICP doc, updated 27 Oct 2026) was treated as authoritative: Philips 2-6x (not 3x), JLL roadmap in eight weeks (not four), outbound floor 501+ employees / ~$250M revenue (not 500+ / ~$200M), Philips and NextPower kept anonymous, no figures in Email 1.
- Every conflict is listed in `company/MEMORY.md` Open Questions for client confirmation.

**Most stealable element:**
Reading a client's vendor-briefing docs as the voice and claims rulebook (approved lines, banned words, retired terms) before any copy is written.

**Do NOT carry over:**
Future Works-specific language rules (no em dashes, anonymous Philips/NextPower, "AI transformation with skin in the game").

**Linked entries:**
- `company/MEMORY.md` → Open Questions
- `company/voice.md` → Approved Claims

**Outcome (to update later):**
Pending client confirmation of the conflicts and the missing contract/infrastructure details.

---

### {{YYYY-MM-DD}} — {{Short title — e.g. "Logged Email 1 v4 as winner (hiring signal)"}}

**Context:**
- Campaign: {{name}}
- Signal: {{signal}}
- Target: {{ICP slice}}
- Metrics: {{sends}} sends, {{PRR}}% PRR, {{meetings}} meetings

**Decision:**
{{What we did — e.g. "Logged Email 1 v4 to copy-library Top Performers. Promoted to default Email 1 for new hiring-signal campaigns."}}

**Why:**
- {{Specific reason 1 — exact phrase, structure, or angle that worked}}
- {{Specific reason 2}}
- {{Specific reason 3}}

**Most stealable element:**
{{The single pattern to replicate elsewhere — e.g. "Specific signal number + named client + dollar saved" structure for Part 1 and 2.}}

**Do NOT carry over:**
{{What is client-specific and should not be templated — e.g. "The $100k saved figure is Future Works-only."}}

**Linked entries:**
- `company/copy-library.md` → {{variant name}}
- `company/test-log.md` → {{test ID if relevant}}

**Outcome (to update later):**
{{Filled in after the decision plays out. E.g. "Promoted to default. Tested on Client B 2 weeks later — also 2.1% PRR. Pattern confirmed."}}

---

### {{Previous entry}}

...

---

## Decisions to Watch

Decisions where the outcome is not yet known. Review these at the next weekly sweep to see if they should be confirmed or reversed.

| Date | Decision | Expected confirmation |
|------|----------|----------------------|
| {{date}} | {{decision}} | {{week ending}} |

---

## Recurring Patterns (cross-decision insights)

When multiple decisions confirm the same pattern, log it here. This is the closest thing to portfolio-level learning within a single client.

- **{{Pattern name}}** — observed in {{n}} decisions. {{Description.}} Use as default for {{situation}}.

---

## Lessons Learned (graveyard reasoning)

Decisions that did NOT work and what we now know not to do.

### {{YYYY-MM-DD}} — {{What we tried}}

**What we tried:** {{description}}
**Why we thought it would work:** {{prediction}}
**What actually happened:** {{result}}
**Root cause:** {{specific reason}}
**Rule:** {{the takeaway — e.g. "Do not use Founder LinkedIn posts as personalisation hook for technical CTO audiences."}}

---

## Notes for Claude

- When asked "why did we pick X for this client?" — search this file first before answering.
- When recommending changes, surface conflicting decisions from this log. If a past decision is being reversed, explicitly say so.
- Never delete entries. If a decision is overturned, log the reversal as a new entry referencing the old one.