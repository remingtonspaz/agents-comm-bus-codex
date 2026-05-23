# agents-comm-bus-codex

Codex marketplace endpoint for the `agents-comm-bus` plugin family.

This repository is intentionally thin. The install model keeps source code and built plugin artifacts in the source monorepo, while this repo exposes only the Codex marketplace catalog at `.agents/plugins/marketplace.json`.

## Current entry

- `agents-comm-bus-telegram` version `0.0.0`
- Source subdir: `plugins/codex/telegram`
- Planned source repository: `https://github.com/remingtonspaz/agents-comm-bus.git`

## Before publishing

- Confirm the source monorepo has been renamed or created as `remingtonspaz/agents-comm-bus`.
- Confirm `plugins/codex/telegram/` exists in the source monorepo and contains the built Codex plugin payload.
- Validate the `git-subdir` source shape against the live Codex marketplace schema.
- Pin a release ref/tag once the first source-monorepo artifact release exists.
- Replace placeholder version `0.0.0` with the release version.
