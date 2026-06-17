# ManagedFolders

ManagedFolders is a Markdown-first operating system for projects, clients, companies, and personal systems. The core idea is simple: folders should not just store files; they should help manage the work.

This repository is the public mirror and roadmap, plus a sterilized SignalDesk outline. Private operating workspaces remain the source of truth for implementation details.

## What ManagedFolders Does

A Managed Folder can organize:

- current state
- decisions
- tasks
- project work
- communications
- durable knowledge
- source evidence
- dashboards and readable task views

## ManagedFolders 2.2

ManagedFolders 2.2 is the current public tracked structure for active operating folders. The model is organized around clear operating layers and a standardized task system:

- Executive: the current operating layer, with separate folders for current state, candidate detection, and approved project management
- Scribe: chronological history, journals, communications, logs, imports, source evidence, and how information was learned
- Admin / Knowledge: durable facts, stable reference knowledge, people and context, systems, operations, and brand or communication standards
- Task Radar: a normally-empty approval gate that scans communications, journals, project notes, documents, and daily activity to surface possible tasks, follow-ups, blockers, unresolved questions, and missing decisions before they get lost
- Project Manager: the source of truth for approved managed work, priorities, dependencies, statuses, and work-session context while Markdown remains the readable interface
- Now / Today: small visible execution surfaces for what to do now and what to remember today

## Public Status

This repo is currently a public mirror and roadmap, not the full private operating workspace.

Current public tracked version: `2.2`

## Repo Shape

- `signaldesk/` - sanitized SignalDesk control-plane outline
- `docs/` - public ManagedFolders documentation, release notes, and version history
- `examples/Example Managed Folder/` - fake public-safe example of the current managed-folder structure

## What Belongs Here

- public-safe notes and roadmap updates
- sanitized registry snapshots
- release notes and progress logs
- public documentation for the ManagedFolders concept

## What Stays Private

- personal paths
- private names and client details
- local machine-specific configuration
- anything that does not need to be public

## Roadmap

The first public release story starts with a self-contained management system and now continues through a visible version log. See [`docs/versioning-roadmap.md`](docs/versioning-roadmap.md) for the public-safe release shape and cadence, [`docs/version-log.md`](docs/version-log.md) for the tracked version updates, [`docs/github-versioning.md`](docs/github-versioning.md) for how GitHub versioning works, [`docs/2.2.md`](docs/2.2.md) for the current release note, [`docs/task-system.md`](docs/task-system.md) for the task system overview, [`docs/task-radar.md`](docs/task-radar.md) for the Task Radar concept, and [`examples/Example Managed Folder/`](examples/Example%20Managed%20Folder/) for a fake example folder.
