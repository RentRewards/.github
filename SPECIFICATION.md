# .github — Specification

## What this is

The organization-wide defaults for RentRewards. A repository named `.github` is
read at the organization level, so certain files here apply across every
repository rather than belonging to this one.

It holds four things and should hold very few more.

## Who reads it

**`profile/README.md` is read by the public.** It renders at
github.com/RentRewards for anyone who visits, including people deciding whether
to work with us.

**Everything else is read by whoever opens a RentRewards repository** — a
researcher looking for how to report a vulnerability, a contributor looking for
the rules.

## What it must do

**Introduce RentRewards without overclaiming.** The profile says what the
platform is and why it exists. It does not name partners, quote metrics, promise
dates, or describe features that do not yet work.

**Give a vulnerability somewhere private to go.** `SECURITY.md` routes reports
through GitHub's private vulnerability reporting rather than a public issue.

**Say what this repository is.** Someone opening it should learn immediately that
a repository named `.github` is special, and which file to edit for a given
outcome.

## Constraints

**Everything here is public.** The repository has to be public for the profile to
render, so nothing internal, confidential or unreleased can live here — including
in a file that seems private by its name.

**GitHub only propagates a fixed list.** Issue and pull request templates,
`CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md`,
`FUNDING.yml`, and `workflow-templates/`. Nothing else here reaches other
repositories, whatever it is named. Agent configuration and shared skills are
distributed as a plugin from `RentRewards/claude`, not from here.

**The profile follows the default branch.** Changing the default branch changes
what the public sees, which is why `main` remains the default and pull requests
choose `development` as their base explicitly.

**Private repositories cannot inherit the health files** on the organization's
current plan, so these defaults reach public repositories only.

## Deliberately not included

**A contributing guide, a code of conduct, or governance.** There are no outside
contributors yet. Writing them now means maintaining documents describing a
process that does not exist.

**Anything project-specific.** Branch rules and definitions of done belong in
each repository's own `CLAUDE.md`.

**Shared workflows or agent configuration.** Those live in `RentRewards/claude`
and are installed, not inherited.

## Amendments

None yet. When a decision here changes, the passage above stays and an entry is
added recording what was planned, what replaced it, and why.
