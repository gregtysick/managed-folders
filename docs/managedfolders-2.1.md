# ManagedFolders 2.1

ManagedFolders 2.1 describes the current public-safe structure for an active operating folder.

## Core Shape

```text
Managed Folder/
  AGENTS.md
  README.md
  managed-folder.config.md
  Inbox/
  _executive/
    current_state/
    task_radar/
    project_manager/
  _scribe/
  Admin/
  Projects/
  Library/
  Repos/
  .archive/
```

## Executive

The Executive layer answers: what matters now?

In 2.1, Executive is split into:

- `current_state` for current state, open loops, next actions, decisions, memory, inbox triage, recurring checks, and compact project registry notes.
- `task_radar` for candidate detection, pending review, scan notes, and reconciliation records.
- `project_manager` for approved tasks, generated views, project dashboards, and optional structured task storage.

The Executive layer is not a document workspace. Documents, deliverables, reusable references, meeting packets, and durable business facts belong in owned lanes outside Executive.

## Scribe

Scribe answers: how did we know this?

It holds journals, logs, communications, imports, source evidence, handoffs, and historical reference material.

## Task Radar

Task Radar proposes possible work.

It should stay review-based. It does not approve tasks automatically.

## Project Manager

Project Manager stores approved work.

It may be simple Markdown, generated Markdown views, a structured database, or a dashboard, depending on the needs of the folder.

## Example

See [`../examples/Example Managed Folder/`](../examples/Example%20Managed%20Folder/) for a fake public-safe folder that shows the current shape.
