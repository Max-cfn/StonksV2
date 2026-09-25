# Stable release sync

StonksV2 follows published stable releases of [Picsou Finance](https://github.com/Zoeille/picsou-finance).

A daily GitHub Actions workflow prepares one deterministic branch per stable release, opens a pull request through the GitHub REST API, runs CI, and merges only after all required checks pass.

Merge conflicts create one review issue per release. An open pull request or review issue pauses later attempts, avoiding duplicate branches and repeated failure notifications.

Upstream development and feature branches are not tracked.
