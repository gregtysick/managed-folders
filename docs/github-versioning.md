# GitHub Versioning

GitHub always records commit history, but version numbers are a human convention.

## Commits

Every commit is a saved checkpoint with a unique hash.

Commits are automatic once they are created locally and pushed to GitHub.

## Version Log

This repository tracks public versions in `docs/version-log.md`.

That file is updated manually when the public story changes.

## Tags

A Git tag is a named pointer to a commit, such as:

```text
v2.0
```

Tags are useful when a version should be easy to find later.

## GitHub Releases

A GitHub Release is a public release page based on a tag.

Releases are useful for downloadable artifacts, formal notes, or public milestones.

## Current Practice

ManagedFolders currently uses:

- commits for normal progress
- `docs/version-log.md` for public version history
- optional tags or releases only when a version needs a formal public milestone
