# MEMORY — Future Works

**Always-loaded scratchpad.** This file is read at the start of every Claude session for this client. It is the "what is currently top of mind" working memory — distinct from the structured logs.

**This file is intentionally lightweight.** It is NOT a permanent archive. Old entries get pruned or moved to `company/decision-log.md` if they become permanent learnings.

---

## Distinction from other files

| File | Purpose | Cadence |
|------|---------|---------|
| `MEMORY.md` (this file) | Active context, transient notes, current focus | Updated mid-session by any skill |
| `company/decision-log.md` | Permanent decision rationale with structure | Updated on decisions |
| `company/comms-log.md` | Communication events with the client | Updated on every interaction |
| `company/copy-library.md` | Winning copy artefacts | Updated weekly |
| `company/test-log.md` | Test history | Updated when tests start / complete |

If something belongs in one of the other files, write it there. Only use MEMORY for transient or evolving context.

---

## Active Focus

- 2026-11-09: Company files filled from `raw/` client documents. Remaining gaps are client-side facts (contacts, contract, SLA, success targets, Instantly infrastructure) marked `{{TO CONFIRM}}`.
- Lead-list analysis and Email 1 drafts already exist in `analysis/` (Oil & Energy v1, industrial machinery). Check them against the ICP before launch (see Watch-outs).

---

## Active Inbound Watch

Accounts where inbound signals fired recently and we are tracking conversion. Items here should be re-checked within 48h-7d.

| Account | Signal | Tier | Activated | Re-check |
|---------|--------|------|-----------|---------|
| (none yet) | | | | |

Cleared from this section when:
- Converted to meeting → move to comms-log
- Replied negatively → suppressed
- Re-check date passed with no engagement → drop

---

## Client Preferences (captured ad-hoc)

From the client's vendor-facing documents:

- Wants vendors to lead with the category line, then the mechanism, then one proof point.
- Prefers a one-page brief over a deck for CEO / board buyers.
- The live site (future.works) is the source of truth for lead-magnet links; flag missing or retired magnets to the Future Works content team.
- Ask the Future Works contact before using market-size figures in any partnership model.

---

## Watch-outs

- **Keep Philips and NextPower anonymous** in outbound, decks and landing pages. Use the approved anonymous lines in `company/voice.md`.
- **No figures in the first cold email.** Proof lines only where the sequence allows.
- **No em dashes** in any client copy. Company name is always "Future Works" (two words).
- **Never "asset-heavy"** in copy. Never "digital transformation", "web design", "digital product".
- **European-only accounts are disqualified** — the most common routing error. Under 501 employees / ~$250M revenue = never outbound.
- **Exclude upstream oil and gas extraction, metals and mining.** The `analysis/` Oil & Energy list is "AllSizes-NoExcl"; filter it before any send.
- **Certifications:** SOC 2 Type II and ISO 27001 are audits in progress. Never say "certified".
- **Most of the 51 website case studies are brand/web work** from the earlier agency era. Only use AI/operations proof plus the approved list.
- **No prices, percentages of fee, or the 15% bonus** in public copy; commercial conversations only.

---

## Open Questions / Pending Items

Conflicts between raw documents (defaulted to the newest doc, the 27 Oct 2026 ICP, until confirmed):

- [ ] **Philips proof:** "3x return" (Positioning, Pitches, Lead Magnets, Market Size, Mission; Sep 2026) vs "2-6x return" (ICP doc Oct 2026 and website). Using 2-6x, anonymous.
- [ ] **JLL roadmap:** "unlocked in four weeks" (Sep docs) vs "eight weeks" (ICP doc). Using eight weeks.
- [ ] **NextPower vs NextTracker** naming and which proof to lead with (75% faster time to market vs 20,000+ work hours a year). Both anonymous now.
- [ ] **Outbound size floor:** 500+ employees / ~$200M (Sep docs) vs 501+ / ~$250M (ICP doc). Using 501+ / ~$250M.
- [ ] **Cycle 1 fee:** ~$400K (ICP) vs $410K (Market Size, PHL-1 SOW). Internal only.
- [ ] Lead Magnets doc says solution briefs map to "five problem domains" but lists four briefs; item 5 is missing from the list.
- [ ] Client contacts, contract, SLA, success criteria, reporting day.
- [ ] Instantly workspace, sending domains, mailboxes, warmup status, tool stack.
- [ ] `raw/onboarding-intake.md` is still a blank template; send it to the client to close the gaps above.

---

## Recent Learnings (not yet codified)

- The client's own copy rules overlap with this OS's rules (no buzzwords, specifics over claims) but add stricter ones: no em dashes, no figures in Email 1, anonymous proof.

---

## Forged Skills (pending review)

Skills auto-created by `gtm-skills/skill-forge.md` from detected patterns. Each forged skill lives at `gtm-skills/forged-{name}.md` until promoted.

**Promotion steps:**
1. Review the forged skill file
2. Refine content if needed (it is a draft)
3. Rename the file to drop the `forged-` prefix
4. Add a row to `CLAUDE.md` routing table
5. Move the entry from this section to a permanent record

**Deletion:** just delete the file. The pattern signature is preserved in `company/session-log.md` Forged skills table so it will not be re-suggested.

| Forged skill | Pattern intent | Date forged | Status |
|-------------|----------------|-------------|--------|
| (none yet) | | | |

---

## Archive

Older entries moved here when no longer top of mind but worth keeping searchable. Prune entries older than 90 days unless they capture something not already in permanent files.

- (none yet)

---

## How Skills Update This File

- **`weekly-reviewer.md`** — at end of review, prompts Harry to update Active Focus and Recent Learnings
- **`reply-handler.md`** — when a reply contains a client preference signal, captures to Client Preferences
- **`client-request-handler.md`** — adds to Open Questions when a request needs client response
- **`inbound-activator.md`** — adds to Active Inbound Watch
- **`incident-responder.md`** — adds to Active Focus if incident is unresolved

## Auto-Pruning Rules

Skills should:
- Remove Active Inbound Watch entries past their re-check date with no conversion
- Move Active Focus items older than 30 days to Archive if no longer relevant
- Move Recent Learnings older than 90 days to Archive or promote to decision-log
- Never delete Watch-outs (these compound permanently)
- Never delete Client Preferences (these compound permanently)
