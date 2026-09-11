# .github

Organization-wide defaults for RentRewards. See `SPECIFICATION.md` for what
belongs here and what GitHub actually propagates, and `PROGRESS.md` for where
the work has got to.

## This repository is public

Everything committed here is visible to anyone, and `profile/README.md` renders
at github.com/RentRewards. Nothing internal, confidential or unreleased belongs
in this repository, whatever a file is named.

Review a change to `profile/README.md` the way you would review anything
published under the organization's name.

## Branches

```
main  ←  staging  ←  development  ←  feat/...
```

`main` is the default branch, which is what the public profile renders from.
Leave it that way: pointing the default at `development` would put unreviewed
work on the organization's front page. Pull requests choose `development` as
their base explicitly.

**Never commit directly to `main`, `staging` or `development`.** `main` and
`staging` are protected on GitHub as well, so a direct push is refused.

**Never push.** Pushing is the user's call, every time.

## Commits and pull requests

The `workflow` plugin is enabled for this repository, so `/workflow:commit`,
`/workflow:plan` and `/workflow:pr-summary` are available and the commit hook is
active. One commit per task, and the message is written to a file in one command
and committed in the next — the hook cannot read a file written by the same
command that commits it.

## Definition of done

There is nothing to build or test. A change is done when the wording says what
was meant, reveals nothing it should not, and the task is ticked in
`PROGRESS.md`.
