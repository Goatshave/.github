# Documentation validation

Reviewed on 2026-10-24, Asia/Seoul.

This repository now contains English Markdown documents and GitHub issue forms.
The organization profile is edited directly. Website source, assets, generated previews, package configuration, and build, check, and preview scripts have been removed.

## Local checks

- Check all retained Markdown links and anchors against local files.
- Check that all retained repository text is English.
- Parse the GitHub issue forms and inspect their required fields.
- Run `git diff --check` for whitespace errors.
- Confirm that the working branch is `main` and that the approved organization profile is unchanged.

These checks do not require a build, package installation, or a committed validation script.
All checks passed: seven Markdown documents, eight local links, English-only text across ten retained files, and both issue forms.
External documentation links were not rechecked during this cleanup, and no GitHub form was submitted.

## Repository history

The final documentation snapshot is prepared as a single initial commit on `main`.
Earlier website code and history are excluded from that branch. No website deployment or pull request is part of this update.
