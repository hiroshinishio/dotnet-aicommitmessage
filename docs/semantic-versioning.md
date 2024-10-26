# Semantic Versioning Automation

This project uses a `prepare-commit-msg` Git hook to automate semantic versioning in commit messages. The hook appends `+semver: minor` to commit messages to ensure consistency and accuracy in version increments.

## Configuration

The hook can be configured to append different semantic versioning levels (`patch`, `minor`, `major`) based on the commit's impact. Adjust the script in `hooks/prepare-commit-msg` to change the default behavior.

## Usage
Simply commit your changes, and the hook will automatically append the semantic versioning tag to your commit message.
