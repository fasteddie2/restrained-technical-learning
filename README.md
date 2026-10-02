# Restrained technical learning

An instructions-only skill for small private technical notes and focused retrieval.
It preserves useful corrections without automatically rewriting agent policy,
creating scheduled work, scanning transcripts, or training a model.

## Use

Copy this repository into `restrained-technical-learning` under your agent's
configured skill directory. Use its supported discovery/registration process and
verify that a fresh session reads `SKILL.md`. There are no hooks or dependencies.

Choose a private notes location under your existing workspace policy. Merely
installing the skill does not authorize new writes. Once authorized, create only
missing LEARNINGS.md, ERRORS.md, and FEATURE_REQUESTS.md files using the blank
headings in `TEMPLATES.md`. Never replace existing notes. Keep actual records out
of this public skill repository.

Example: "Record the verified parser correction in my approved private technical
notes, deduplicating the incident and keeping unresolved causes labeled as such."

For read-only use: "Consult relevant prior lessons for this parsing task without
writing or modifying notes."

An ignore rule is not encryption, access control, or protection for already
tracked files. Check sharing, sync, backup, and Git behavior for the chosen
location. Removing this skill does not authorize deleting the notes; preserve
them as user data. No production notes or real incidents are distributed here.

## Attribution

Adapted from [pskoett/self-improving-agent v4.0.2](https://clawhub.ai/pskoett/skills/self-improving-agent),
whose listing specifies MIT-0. This is an independent adaptation, not an upstream
release or endorsement. It retains concise lessons and deduplication while
omitting automatic policy promotion, hooks, transcript sweeps, scheduled reviews,
and cross-session actions. Upstream scripts and hooks are not included.

License: MIT-0; see `LICENSE`. See `VALIDATION.md` for review scope and limitations.
