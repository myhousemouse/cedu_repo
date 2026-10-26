# Research source map

Status: Baseline sources reviewed; authenticated research pending

## Current official web properties

Treat each site as a separate observation target until their relationship has
been established from evidence.

| ID | URL | Initial status |
| --- | --- | --- |
| WEB-01 | `https://www.cedubook.com/` | Public home and navigation reviewed 2026-10-26 |
| WEB-02 | `https://cedugroup.com/` | Public home and business portfolio reviewed 2026-10-26 |
| WEB-03 | `https://cedulearn.com/` | Public metadata reviewed 2026-10-26; rendered authenticated interface pending |

For later research, record the access date, page URL, page title, relevant
observation, and whether the material is current, archived, or inferred.

## Historical reference vault

- Repository: `https://github.com/myhousemouse/experience`
- Local checkout: `/workspace/experience`
- Relevant directory:
  `/workspace/experience/Cedu-ServicePlanning-Obsidian-Vault`
- Start with: `README.md`
- Primary index: `00_Index/쎄듀 서비스기획팀 업무 경험.md`

The checkout uses Git sparse checkout so only the relevant vault is present in
the working tree while repository history remains available.

### Usage rules

- Use this vault as historical first-party context supplied by the user.
- Do not modify the reference repository unless the user explicitly requests
  it.
- Do not copy private or personal material into public-facing deliverables
  without checking relevance and sensitivity.
- Date-check historical claims against current official sources.
- When a finding relies on the vault, cite the exact relative file and, when
  relevant, its Git commit or document date.
- Distinguish recorded historical fact, the original author's interpretation,
  and a new analysis derived from it.

## Source precedence

Use sources according to the question being answered:

1. Current official service pages for present-day observable behavior
2. User-supplied internal or historical records for past context
3. Official announcements and policies
4. App stores, public reviews, and third-party market sources
5. Analyst inference, always labeled as inference

Conflicts should be recorded rather than silently resolved.

## UI/UX reference source

For UI/UX analysis, use the UI Bowl (`uibowl`) plugin when it is available in
the session. Treat its results as comparative design references, not proof that
the same solution will work for CEDU.

For every cited example, retain:

- Service or product name
- Source URL or plugin-provided reference
- Screen, flow, or interaction pattern
- Date accessed
- Relevant observation
- Why it supports the analysis
- Differences or limitations when applied to CEDU

If the plugin is not attached to the current session, disclose that limitation
and do not imply that its database was searched.
