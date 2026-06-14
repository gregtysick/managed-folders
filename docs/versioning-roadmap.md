# ManagedFolders Versioning Roadmap

ManagedFolders is being published as a public mirror and roadmap for the private operating-system work behind the project.

## 2.0 Direction

Upcoming public updates will gradually document:

- the Managed Folder layer model
- Task Radar
- Project Manager
- dashboards and readable views
- install and setup guidance
- public-safe templates

The goal is small, regular public-safe updates when there is meaningful progress.

## Release shape

- `1.0` introduced the project as a self-contained management system.
- `1.1` begins the public versioning log and explains the first visible changes.
- Intermediate `1.x` documentation releases remain optional.
- `2.0-preview` established the active layer model, Task Radar, and the Project Manager boundary.
- `2.0` is the current public tracked operating-model release.
- Later releases should note what changed, what was added, and what is still under development.

## Current version tracking

- Current public tracked version: `2.0`
- Current public release note: [`2.0.md`](2.0.md)
- Version updates are recorded in [`docs/version-log.md`](version-log.md).
- Each version entry should briefly state what changed and why it matters.
- GitHub commits are automatic history, but version labels, tags, and releases are maintained deliberately. See [`github-versioning.md`](github-versioning.md).

## Version update workflow

For each public version:

1. Add or update a short release note in `docs/`, such as `1.0.md` or `2.0.md`.
2. Add the version to `version-log.md`.
3. Update `docs/README.md` so the release note is easy to find.
4. Update the root `README.md` only when the current public tracked version changes.
5. Keep the wording public-safe and avoid private paths, names, and implementation records.
6. Commit the documentation update.
7. Add a Git tag or GitHub Release later only when a durable public artifact is needed.

## Release cadence

- Publish small, sanitized updates on a regular cadence.
- Aim for a new public update when there is enough meaningful new material to show.
- Keep the public repo readable as a progression, not a dump of internal notes.

## Public-safe rules

- Do not publish personal paths.
- Do not publish private names or client details.
- Do not expose local machine-specific configuration.
- Treat private operating workspaces as the source of truth and the public repo as a mirror.

## Working notes

- The release workflow can become a template or script later.
- The manager should help draft each release note and choose what is safe to publish.
- The goal is to show a clear progression from seed project to mature public record.
