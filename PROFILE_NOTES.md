# Profile review notes

Review edition, 20 October 2026, on `codex/personal-project-shelf`. The main profile changes only after this branch is merged. No remote profile settings, descriptions, homepages or pins were changed.

## Suggested six pins

This order follows the README's mix of playful builds, local utilities and inspectable experiments:

1. `common-grounds-makeathon` — The Commons.
2. `screenshot-declutterer` — Screenshot Declutterer.
3. `hr-2026` — Plotline.
4. `theFastandtheFungible` — ResearchAgent.
5. `yald` — Yet Another LLM Dashboard.
6. `talktoit` — Apple Health questions and ingestion.

Swap yald for `rewind-app` or `dc2` to give team coursework more space. These are recommendations, not applied changes.

## Description drafts

- `common-grounds-makeathon`: The Commons: wish for a creature from your phone and watch it enter a shared cartoon room. Solo Common Grounds makeathon build.
- `screenshot-declutterer`: A local macOS workspace for sorting screenshots, reviewing similar images and confirming recoverable Trash cleanup. Optional on-device naming.
- `hr-2026`: Plotline: compact forest-map decision layers, a review interface and retained checks that the written screening rules return the same answers.
- `theFastandtheFungible`: ResearchAgent: a team research-desk demo with budgeted evidence buying, proof checks, challenges and refunds. Fictional corpus; XRPL Testnet.
- `yald`: Read-only local coding-agent usage dashboards and portable reports. Public preview; cost estimates are API list-price equivalents.
- `talktoit`: Ask questions of Apple Health exports with a self-hostable importer, DuckDB analytics and local defaults. Optional remote modes.
- `rewind-app`: Rewind: a team-built group time-capsule prototype for collecting moments and revealing them later.
- `dc2`: FlickPond: our course team's upload-to-MP4/HLS video platform, with bounded workers and retained AWS proof runs.

Potential profile bio: “Building things in Singapore. Local tools, shared rooms, and experiments that keep the evidence.”

Keep the existing portfolio homepage. ResearchAgent's removed Cloud Run service should not be used as a live homepage. Repository links are the safest default until the parent verifies individual hosted experiences.

## Scope and evidence

The old resume layout, Technical Skills, language logos, statistics card and duplicate social panel are removed. The shelf uses nine authentic project screenshots and one clearly labelled aggregate proof figure. Images link to their project or a full-size local image; plain text carries the claims even without images.

Primary evidence: the completed portfolio GitHub/LinkedIn research dated 20 October 2026, public repository files, final published post wording, and the official SUTD release linked in the README. Immutable public image sources and transformations are in ASSET_SOURCES.md.

This actual checkout is separate from the unpublished `../collaboration95` draft. The website and that draft were not modified.

## Verification completed

- GitHub's GFM renderer was called through `gh api markdown`; the resulting sanitized HTML was inspected locally with a GitHub-like light/dark shell, not on an unpublished GitHub branch.
- All 10 images decode successfully, have useful alt text, and total 693,414 bytes (about 677 KiB). All repository-relative links resolve. SVG parses successfully.
- Desktop width 1000 px: cleanup screenshots share a row, ResearchAgent has three panels, and the game images form a ribbon. Width 360 px: images wrap, all 10 load, and document width remains exactly 360 px with no horizontal overflow. The dark preview was inspected too. No motion or scripts are required by the README.
- All 18 distinct linked public repositories resolved through authenticated `gh api`. The Plotline proof path and public benchmark gist also resolved.
- Portfolio and official SUTD source returned HTTP 200. LinkedIn rejected the HEAD probe with HTTP 405; its known profile URL is retained from the supplied research rather than claiming an anonymous live-page check.
- `git diff --check` passes. The prepared changes are scoped to `codex/personal-project-shelf`.

Temporary review shell: `/tmp/profile-shelf-preview-20261020/index.html` and `dark.html`, served at `http://127.0.0.1:8796/` while its local server is running. GitHub-rendered HTML: `/tmp/profile-shelf-rendered-20261020.html`. Validation record: `/tmp/profile-shelf-validation-20261020.json`. These review files are outside the checkout.

The integrated review corrected the Fitback paragraph to say the older runtime is isolated in a worker; the follow-up found no remaining actionable issue.
