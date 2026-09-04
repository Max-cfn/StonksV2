# Stable release sync

StonksV2 follows published stable releases of [Picsou Finance](https://github.com/Zoeille/picsou-finance).

A daily GitHub Actions workflow opens a pull request for a new stable release. It enables auto-merge only after the required CI checks pass.

Merge conflicts create one review issue per release. While that issue remains open, later checks succeed without retrying, avoiding repeated failure notifications.

Upstream development and feature branches are not tracked.
