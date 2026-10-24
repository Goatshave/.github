# Source review and open decisions

## Review baseline

The initial review was conducted on 2026-10-24, Asia/Seoul, before the owner removed the remote organization-profile repository.
This is a historical source snapshot, not a claim that repository settings or counts remain unchanged.
No remote settings were changed or rechecked during the documentation-only cleanup.

The original `.github` repository contained only `profile/README.md` at commit `04e1da24acda69ae89203142c57d7bb729ef9459`.
Its introduction emphasized specialists, strict review, and painful participation, with no project or contribution routes.
The owner subsequently requested an English profile centered on shared interests, people, and collaboration, without a project listing.

## Verified project context

The initial organization listing contained nine public repositories, including seven forks. Forks were excluded from authored project descriptions and were not deleted.
The non-fork repositories were `.github` and `open-grid`.
No organization-wide website, general email, or chat channel was verified at that time.

Open Grid was reviewed at [`a686580`](https://github.com/Goatshave/open-grid/tree/a686580311c1918c684154ab54eaa41e75f1630b):

- A public MIT-licensed TypeScript data grid with a framework-independent core and React, Vue, and Svelte layers.
- Sorting, filtering, editing, selection, grouping, tree data, virtualization, and server request workflows were present in source, documentation, and tests.
- The [0.3.0 release](https://github.com/Goatshave/open-grid/releases/tag/open-grid-v0.3.0) and [release record](https://github.com/Goatshave/open-grid/blob/a686580311c1918c684154ab54eaa41e75f1630b/docs/release.md) were public.
- The [documentation site](https://goatshave.github.io/open-grid/) returned HTTP 200. Local examples were documented; no separate public demo was verified.
- Existing contribution, conduct, security, and license documents remain project-specific.

No Open Grid source, public API, or README was changed. The library's complete test suite and package-installation checks were not repeated for this documentation task.

## Reference and editorial choices

[Crafter Station's GitHub profile](https://github.com/crafter-station) and its [profile source](https://github.com/crafter-station/.github/blob/main/profile/README.md) informed the separation of identity, interests, and conversation links.
Its wording, members, activity counts, project portfolio, and contact channels were not copied.

The nonprofit identity is the owner's requested direction, not proof of incorporation.
No people, testimonials, events, sponsors, or performance claims were invented.
A public GitHub identity was not treated as consent for a separate people directory.

## Open decisions

- Adoption of the operations draft, project ownership, access, handover, and financial transparency procedures.
- Organization-wide confidential reporting contacts and an alternative for conflicts of interest.
- Any future people directory and the consent required for each detail.
- A license for these organization documents. Open Grid's MIT license does not automatically cover this repository.
- The website's separate repository, hosting, and domain. All website code and tooling have been removed from this repository.

The organization repository contains documentation and issue forms only. Website work remains separate.
