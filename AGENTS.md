# Deprecated sys-monitor-tauri — Agent Instructions

This repository is a deprecated **documentation-only scaffold**. It currently contains no application implementation. Maintained system-monitor work belongs in `quantdale/monitorers` unless an explicit task says otherwise.

## Fail-closed repository identity

Before planning or coding, inspect the current tree. Do not invent Tauri, Rust, Node, frontend, test, build, or packaging commands that are not present. The repository name is not evidence that an application exists.

Required reading:

1. `README.md`.
2. `.agent/STATE.md`.
3. `.agent/PLANNER_HANDOFF.md`.
4. `.agent/EXECUTION_PROMPT.md` only if one is later created.

Harness-specific adapters are subordinate to this file.

## Maintenance posture

- Default to preserving this repository as a deprecated placeholder.
- Do not start feature development here merely to make the name match the maintained monitor project.
- If revival is explicitly requested, plan it as a new architecture/bootstrap effort with concrete requirements, commands, validation, and migration intent.
- Never claim a build/test/runtime result until a real implementation and executable validation surface exist and have been run.

## Documentation and history

Keep living docs truthful about the absence of implementation and the deprecation boundary. Historical commits/adapters remain historical evidence and should not be rewritten to imply an application once existed here if the tree does not prove it.

Evidence precedence: `current repository contents and executable evidence` > `active state/prompt` > `living docs` > `historical records` > `assumptions`.

## Git safety

Do not force-push, rewrite history, discard unrelated work, or use destructive cleanup. Any revival or migration must be explicit, reviewable, and separately validated.
