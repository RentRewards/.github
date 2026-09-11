# .github — Progress

**Phase 2 of 2 · P2-M02 in progress · 3 of 4 milestones complete**

## How this file works

- Work happens only on the milestone marked 🔄 IN PROGRESS.
- A task is ticked when its commit lands, not when it feels done.
- Work that isn't in the spec becomes a new task, milestone or phase here, and
  an amendment in `SPECIFICATION.md` if it changes what the project is.

---

## Phase 1 — A presence worth having ✅ COMPLETE

What the organization looks like to someone who finds it, and where a
vulnerability goes.

### P1-M01 — The public profile ✅ COMPLETE

**Branch:** `main` · the repository's first commits

#### Tasks
- [x] Write `profile/README.md`: what RentRewards is and why it exists
- [x] Keep it conservative: no partners, no metrics, no dates, no unbuilt features
- [x] Document the repository itself in `README.md`

### P1-M02 — A private channel for vulnerabilities ✅ COMPLETE

**Branch:** `main`

#### Tasks
- [x] Write `SECURITY.md` routing reports through private vulnerability reporting
- [x] Avoid publishing a contact address on a public repository
- [x] Enable private vulnerability reporting on the organization

---

## Phase 2 — Working conventions 🔄 IN PROGRESS

Bringing the repository onto the shared workflow.

### P2-M01 — A specification and a tracker ✅ COMPLETE

**Branch:** `chore/p2-adoption-docs`

#### Tasks
- [x] Write `SPECIFICATION.md`: what belongs here and what GitHub actually propagates
- [x] Write `PROGRESS.md`: what has been done and what is left
- [x] Record the branch and commit rules in `CLAUDE.md`

### P2-M02 — The conventions enforced 🔄 IN PROGRESS

**Branch:** `feat/p2-m02-enforce-conventions`

#### Tasks
- [ ] Enable the workflow plugin at project scope, as the other repositories have
- [ ] Confirm the commit hook refuses a commit on a protected branch here

---

## Outstanding, not yet a phase

**A marketplace description.** `claude plugin validate` warns that the
marketplace in `RentRewards/claude` has none. Recorded here because it was found
while working on these repositories, and belongs to that one.

**Community health files.** A contributing guide and a code of conduct become
worth writing when there are outside contributors. There are none yet.
