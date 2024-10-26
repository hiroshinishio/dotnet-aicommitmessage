# Configuration

The `prepare-commit-msg` hook can be configured to append different semantic versioning levels based on the commit's impact. Modify the script in `hooks/prepare-commit-msg` to change the default behavior from `+semver: minor` to `+semver: patch` or `+semver: major` as needed.

Ensure to test the hook in different environments to confirm its reliability.
