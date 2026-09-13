This patch fixes code-block scroll jumps and disappearing content in Reading view and Live Preview.

## What's New

- Code-block formatting updates locally without refreshing the entire Reading view.

## Bug Fixes

- Fix notes jumping when editing code blocks beside a Reading view pane, including changes to the language, content, or options such as `static` ([#67](https://github.com/felixleopold/obsidian-code-suite/issues/67)).
- Fix blank content below large blocks after scrolling through them and collapsing them in Reading view.
- Keep duplicate code blocks and blocks in separate editor panes independent, preserving the correct block state through edits.
- Remeasure Live Preview blocks when collapse, output, or embedded content changes their height.

## Upgrade Notes

- No settings changes or manual migration are required.
- Thanks to @luckman212 for the detailed report and investigation.

See [PR #69](https://github.com/felixleopold/obsidian-code-suite/pull/69).
