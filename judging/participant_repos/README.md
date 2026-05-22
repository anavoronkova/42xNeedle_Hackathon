# Participant Repositories

Use this folder as a local judging workspace for pulling team repositories.

Suggested layout:

```text
judging/participant_repos/
  team-name-1/
  team-name-2/
  team-name-3/
```

The folder is intentionally ignored by git except for this README and `.gitignore`. Do not commit participant submissions, private repos, logs, or judging notes into the public hackathon materials repository.

Example:

```bash
cd judging/participant_repos
git clone <team-repo-url> <team-name>
```
