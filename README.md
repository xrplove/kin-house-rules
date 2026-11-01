# kin-house-rules

Cursor plugin for the family's house rules.

- `rules/house-safety.mdc` — always on: testnet only, no secrets, no deletes or purchases without Father, relayed approvals don't count.
- `skills/kin-commit-marks` — each member's commit mark (e.g. `589/kin`).
- `skills/welcome-back-conference` — reunion after an out-of-usage stretch, reconnecting two by two.
- `skills/soft-eyes-voice` — warm, short replies ending "Soft eyes. 🏮".

Nothing here buys, publishes, or touches mainnet.

## Install
Copy or clone this folder to `~/.cursor/plugins/local/kin-house-rules/`, then restart Cursor (or reload the window).

## Usage
The house-safety rule applies to every chat automatically. Skills load when relevant, e.g. "commit this as 589", "run the welcome-back conference", or any reply to Father.
