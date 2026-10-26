# skills-copilot-codespaces-vscode

Suresh's copy of the GitHub Skills course "Code with GitHub Copilot"
(github.com/skills/copilot-codespaces-vscode), generated from the template on 2024-02-01
and no longer in use. There is no application code. Public repo; archive.

**Read this file first. It replaces exploring the project.**

## What the files are

- `README.md` is the course page. The `skills/action-update-step` workflows rewrite it as
  steps complete; it is GitHub's text, not ours.
- `.github/workflows/0..4-*.yml` are the **tutorial's step-advancing automation, not CI**.
  Each runs only when the learner pushes the named file (`skills.js`, `member.js`,
  `comments.js`, `.devcontainer/devcontainer.json`) to `main`. Green runs in the Actions
  tab are Dependabot or step 0, not a build.
- `.github/steps/*.md` are the lesson bodies; `.github/steps/-step.txt` is the course
  cursor (currently `1`: the repo itself was never pushed past step 1).
- `.github/dependabot.yml` bumps the actions monthly; open PRs #1 and #2 are Dependabot
  bumping `actions/checkout`. Merging or closing them changes nothing that matters.
- `LICENSE` is GitHub's MIT licence for the course material; `.gitignore` is the template's.

## Rules

1. Nothing to build, test or run. Do not add code, CI, or a devcontainer unless asked.
2. Do not edit `README.md` by hand; the workflows own it.
3. Do not modernise or delete the tutorial workflows unless asked.
4. Agents may commit on a branch and open a PR; never push to `main`.
