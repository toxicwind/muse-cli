# Changelog

Auto-backfilled from git history 2026-11-02 (real commits only).

## 2026-10-30
- chore(eidos): apply bun-scaffold bunfig + infra drop-in env (qdrant/hindsight/kafka/redis) — eidos is the pare (0b46db7)

## 2026-10-22
- rig: muse-cli Phase-B autonomous rig — bin/run (uv venv CLI), bin/check (smoke pytest gate), mise tasks (b0e61b0)

## 2026-10-16
- snapshot: round-2 forward-commit 2026-10-16 (7305659)
- snapshot: forward-commit dirty worktree 2026-10-16 (pre weave-land) (858256c)

## 2026-10-01
- Add tests/test_smoke.py: 5 dependency-free smoke/regression tests (8de07a3)

## 2026-09-30
- Maximalize toxicwind fork: repoint README/site to fork, fix stale TLS notes, add smoke tests (628fa52)
- First-class hatch/ipnext agent profile: profiles/hatch-agent.md, docs/ESTATE.md, repoint to toxicwind fork (521b49e)

## 2026-09-27
- Redesign site per redesign-existing-projects skill (bcd5ee1)
- Add Firebase-hosted site, agent demo screenshot, website badge (8982a95)
- Bump version to 0.3.2 (d5caff2)
- Fix #1: verify TLS cert on gateway WebSocket (9406cbb)

## 2026-09-23
- Bump version to 0.3.1 (8765dea)
- Treat a confirmed muse.ai tab as success during auth export. (d5bab66)
- Bump version to 0.3.0 (090473a)
- Notice a newer release once a day and add muse-cli update. (09d2214)
- Bump version to 0.2.2 (6a06a56)
- Guide Chrome remote debugging during auth export and refresh the README hero. (a6c45d1)
- Bump version to 0.2.1 (459ed4a)
- Onboarding fixes: agent-browser install step, missing-binary hint, PATH note (4933a88)
- Add AGENTS.md with release instructions (efcc130)
- CI: bump actions to Node 24 majors, build on main and PRs (7babfb3)
- Bump version to 0.2.0 (first PyPI release) (1413922)
- Package for PyPI: pip/uv/pipx installable muse-cli (3876613)

## 2026-09-12
- Dogfood fixes: poll-based send, safe auth export, input validation (c0f3e5b)
- Fix send race: single frame consumer, graceful watch fallback (809fa2c)
- install.sh: copy skill contents to avoid nested duplicate (55a4da5)
- README: search-friendly intro wording (b65605c)
- install.sh: don't follow stale symlink, reuse existing venv (107d6c5)
- Use uv for everything: installer venv+launcher, docs, skill (de4e795)
- Add curl installer (CLI + skill) and use it in README/skill (1b705f1)
- Skill: assume bare machine, install from scratch first (50859a9)
- Add muse-cli agent skill (install check, auth setup, usage) (23e489f)
- README: recommend muse-cli link name (muse clashes with Muse Code) (e218ed2)
- README: replace mermaid diagram with generated flow image (c2d2ba6)
- muse: CLI for your personal muse.ai agent (943c4b7)
