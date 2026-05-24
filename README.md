# agents-comm-bus-codex

Codex marketplace endpoint for the `agents-comm-bus` plugin family.

This repository is intentionally thin. The install model keeps source code and built plugin artifacts in the source monorepo, while this repo exposes only the Codex marketplace catalog at `.agents/plugins/marketplace.json`.

## Current entry

- `agents-comm-bus-telegram`
- Source subdir: `plugins/codex/telegram`
- Source repository: `https://github.com/remingtonspaz/agents-comm-bus.git`

## Before publishing

- Confirm `plugins/codex/telegram/` exists in the source monorepo and contains the built Codex plugin payload.
- Pin a release ref/tag once the first source-monorepo artifact release exists.
- Track the plugin version in the plugin payload's `.codex-plugin/plugin.json`.
