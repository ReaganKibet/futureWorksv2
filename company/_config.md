# Client Config — Future Works

Central source of truth for variables used across this OS. Other files reference this file rather than hardcoding values.

**Updated by:** `gtm-skills/client-onboarder.md` during setup, then manually maintained.
**Filled from:** `raw/` documents (FW positioning, ICP, buying triggers, elevator pitches, lead magnets, market size, mission/values, case studies), 2026-11-09.

---

## Identity

| Key | Value |
|-----|-------|
| `client_name` | Future Works (two words, always) |
| `industry` | Outcome-based AI transformation services ("AI transformation with skin in the game") |
| `website` | https://future.works |
| `geography` | Target market: United States (primary) and Canada (full scope). European-only accounts disqualified. |
| `primary_contact_name` | {{TO CONFIRM}} |
| `primary_contact_email` | {{TO CONFIRM}} |
| `service_type` | {{TO CONFIRM — DFY / DWY / Custom}} |
| `start_date` | {{TO CONFIRM}} |
| `reporting_day` | {{TO CONFIRM}} |

## Instantly

| Key | Value |
|-----|-------|
| `instantly_workspace_url` | {{TO CONFIRM}} |
| `instantly_workspace_id` | {{TO CONFIRM}} |
| `mcp_connected` | {{TO CONFIRM}} |

## OS

| Key | Value |
|-----|-------|
| `template_version` | 1.6.0 |
| `os_setup_date` | 2026-11-09 |
| `last_review_date` | {{TO CONFIRM — no review run yet}} |

## Source documents (raw/)

| Document | Version / date |
|----------|----------------|
| FW ICP: Ideal Customer Profile and Segments 2025+ | ICP and Positioning Lock v1.0 (R11), updated 27 Oct 2026 (newest, wins on conflicts) |
| FW Positioning, Problem, Solution, Guarantee and more (Vendors) | Positioning R11, updated 4 Sep 2026 |
| FW Customer Buying Triggers & Signals | R11, updated 4 Sep 2026 |
| FW Elevator Pitches (1, 3, 5 min) | R11, updated 4 Sep 2026 |
| FW Current Lead Magnets | R11, updated 4 Sep 2026 |
| FW Market Size | R11, updated 4 Sep 2026 |
| FW Mission, Vision, Values | R11, updated 4 Sep 2026 |
| Future_Works_Clients - Case Studies.csv + futureworks-case-studies.md | Scraped from future.works/work, 3 Nov 2026 |
| onboarding-intake.md | Blank template (not filled by client) |

---

## How Other Files Reference This

When a file needs CLIENT_NAME, INDUSTRY, etc., it points here rather than duplicating. Example pattern:

```
**Client:** see company/_config.md → client_name
**Industry:** see company/_config.md → industry
```

This way: rename a client once (here), and the rest of the OS stays consistent.

## Setup Status

- [ ] All placeholders resolved (remaining: contacts, contract, SLA, success targets, Instantly workspace, sending infrastructure)
- [ ] Instantly MCP connected and verified
- [ ] Reviewed by Harry before first campaign launch
