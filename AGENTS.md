# Agent instructions

## Current phase

This repository is in the product-planning phase. Do not create application
code, package manifests, infrastructure, or implementation scaffolding unless
the user explicitly changes the phase.

## Start every session

1. Use the existing checkout at `/workspace/cedu_repo`. Do not create a Git
   worktree unless the user explicitly requests one.
2. Read this file and `docs/README.md`.
3. Read `docs/current-state.md`, `docs/product-brief.md`,
   `docs/requirements.md`, `docs/open-questions.md`, and
   `docs/research/source-map.md` before proposing work.
4. Review relevant records under `docs/decisions/` and research under
   `docs/research/` when the task touches those subjects.
5. When prior CEDU context is relevant, consult the read-only reference vault at
   `/workspace/experience/Cedu-ServicePlanning-Obsidian-Vault`, beginning with
   its `README.md` and `00_Index/쎄듀 서비스기획팀 업무 경험.md`.
6. Check `git status` in both repositories and preserve all existing changes.

## Planning rules

- Keep confirmed facts, assumptions, proposals, and unresolved questions
  clearly distinguished.
- Do not silently turn an assumption into a product decision.
- Ask for user input when a choice materially changes the product direction.
- Keep documents concise and update existing canonical documents instead of
  creating competing versions.
- Record durable product or technical decisions in `docs/decisions/` using the
  template in that directory.
- Put source-backed investigation notes in `docs/research/` and include links
  or citations where available.
- Treat the reference vault as historical context, not automatically as current
  truth. Preserve its original files and record any reused claim's source and
  date in this repository.
- Keep `/workspace/experience` read-only unless the user explicitly requests a
  change to that repository.
- Do not add secrets, private credentials, or personal data to the repository.

## UI/UX research

When a task involves UI/UX analysis and the UI Bowl (`uibowl`) plugin is
available in the current session:

1. Use UI Bowl to find comparable screens, interaction patterns, and relevant
   reference services.
2. Record the service or product name, source URL or plugin-provided reference,
   screen or pattern, and access date.
3. Explain what the example demonstrates and why it supports the finding or
   recommendation; a screenshot or similarity alone is not evidence.
4. Describe the important difference between the reference context and CEDU's
   users, content, journey, and constraints.
5. Keep observed facts, interpretation, and proposed application separate.
6. Prefer multiple relevant examples when making a broad pattern claim.

Do not claim that UI Bowl was used when its tool is unavailable. In that case,
state the limitation and use other permitted, source-backed research methods.

## End every planning task

Before finishing a task that changes the plan:

1. Update the relevant canonical documents.
2. Update `docs/current-state.md` with the latest agreed state, active topic,
   next recommended action, and unresolved blockers.
3. Update `docs/open-questions.md` when questions are answered or discovered.
4. Summarize exactly what changed and what still needs a user decision.

