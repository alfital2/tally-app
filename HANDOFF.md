## Status

The standalone Tally site now presents drag-and-drop task handoff between Claude Code and Codex alongside its existing dual-provider usage and session monitoring. The live popover mock demonstrates a complete Codex-to-Claude move: the source row collapses, the destination row appears, and both provider summaries update before the loop resets. The feature grid includes a concise explanation. The static page parses cleanly and was visually reviewed at desktop width.

## Recent changes

- Added a restrained cursor-and-session animation directly to the existing Tally popover mock so the handoff is demonstrated in the product UI rather than as a separate illustration.
- Added a sixth feature card explaining that local conversation and repository state move with the task, including the exhausted-source-agent use case.
- Updated hero and metadata copy to make handoff discoverable without changing the page's core limits-monitor positioning.
- Rebalanced the feature grid into two even rows of three and preserved a no-animation experience for visitors who prefer reduced motion.
- Completed the demo's landing state so it changes the real-looking provider lists after the cursor drops the session instead of merely fading out a floating drag ghost.

## Open questions / blockers

- The Tally app handoff implementation is ready to merge, but a new downloadable app release will still be needed before the website's latest-download link delivers this advertised feature.
- The pre-existing untracked `index-future.html` concept remains untouched.

## Next steps

1. Confirm the public GitHub Pages deployment completes after this approved push.
2. Ship an app release containing session handoff so the download matches the website.

_Last updated: 2026-08-31 by Codex_
