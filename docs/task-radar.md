# Task Radar

Task Radar is a proactive open-loop detection concept for ManagedFolders.

It is designed to review recent activity and surface:

- possible tasks
- follow-ups
- blockers
- unresolved questions
- missing decisions
- items that may need human review

Task Radar does not approve work automatically.

It proposes candidates for review.

Approved work belongs in the Project Manager layer.

## Example Signals

- A meeting note mentions that someone will follow up.
- A document includes an unresolved question.
- A communication implies a next step.
- A decision creates implementation work.
- A task appears to be blocked by another unfinished item.

## Safety Principle

Task Radar should prefer fewer, better candidates over noisy extraction.
