# Shared GitHub defaults

This public repository provides default issue and pull request templates for repositories owned by `Jun9u`.

## How it works

- GitHub uses `.github/ISSUE_TEMPLATE/*.yml` only when a repository has no valid local issue templates or issue-template configuration.
- GitHub uses `.github/PULL_REQUEST_TEMPLATE.md` only when there is no repository-specific pull request template.
- This is an account-wide fallback. It cannot selectively exclude repositories.
- Issue types, labels, and GitHub Projects statuses are managed separately; placing a file here does not create or synchronize them.

## Issue categories

- **Task:** actionable work with explicit completion criteria
- **Feature:** a proposed new capability
- **Bug:** unexpected behavior and steps to reproduce
- **Research:** investigation to support a decision
- **Experiment:** reproducible comparison or evaluation

Choose one form according to the kind of work. Use the repository's issue type, area label, and priority label where they are available. No form automatically assigns labels.

## Shared label vocabulary

The `labels.json` file documents the shared set of 11 labels. It is **a reference definition, not an automatic label synchronizer**. Existing repositories may manage their label definitions separately.

Existing project-specific conventions should be preserved when they are more appropriate.
