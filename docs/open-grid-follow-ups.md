# Open Grid documentation follow-ups

Reviewed on 2026-10-24, Asia/Seoul, at Open Grid [`a686580`](https://github.com/Goatshave/open-grid/tree/a686580311c1918c684154ab54eaa41e75f1630b).
These are evidence-based candidates, not assigned work, confirmed bugs, or a new roadmap.
No Open Grid files or public APIs were changed in this organization-documentation task.

## Contribution candidates

### Clarify compatibility validation versions

The [getting-started guide](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/docs/getting-started.md#compatibility) lists React 19.2.8, Vue 3.5.41, and Svelte 5.56.8 as release validation versions.
At the same revision, maintained [React](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/examples/react-basic/package.json), [Vue](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/examples/vue-grouped/package.json), and [Svelte](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/examples/svelte-grouped/package.json) examples declare ^19.3.1, ^3.5.44, and ^5.57.2.

First establish whether the table describes historical release evidence or current CI.
Check the lockfile and verification results before changing its meaning or values. Preserve framework lower bounds and peer dependencies.

### Investigate accessibility differences found in real use

The [roadmap](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/docs/roadmap.md) invites evidence from keyboard, screen-reader, forced-colors, and mobile integrations.
Existing [keyboard](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/e2e/accessibility-keyboard.spec.ts), [display and reflow](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/e2e/accessibility-display.spec.ts), and [automated accessibility](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/e2e/accessibility.spec.ts) tests already cover these areas.

Report the environment and a minimal reproduction first. Add regression coverage only for a demonstrated gap; do not invent a defect to create a starter task.

### Share server-data integration problems

Request cancellation, retry, and stale-response protection already exist in the [core](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/packages/core/src/server-request.ts), [guide](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/docs/server-data.md), and [framework tests](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/e2e/framework-server-lifecycle.spec.ts).
A useful report identifies a real integration difficulty and explains query ownership and successful data commits. Do not propose existing functionality as missing work.

Check current issues and discuss scope before starting any candidate. No starter-task label or maintainer assignment is implied here.

## Separate README improvement proposal

At the reviewed revision, the README was approximately 41 KB and 314 lines.
A separate documentation change could keep purpose, installation, package choice, minimal usage, compatibility, contribution, and license links near the top.

Link detailed functionality to existing package and framework guides. Consolidate maintainer commands with CONTRIBUTING, release, and performance documentation without dropping required checks.
Preserve existing headings and anchors, including `#current-foundation`, `#examples`, `#development`, `#react-ui-usage`, and `#try-it-locally`, as navigation stubs if content moves.
Validate relative and external links and installation examples. Keep that work separate from library and public API changes.
