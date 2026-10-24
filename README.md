# chesseye

Autonomous theme-agnostic Android chess overlay: 2-corner board calibration, local-perimeter highlight-immune vision + legal-move Bayesian tracker, closed-loop gesture verification with fallbacks, and dual Stockfish 19 + distilled SCReLU NNUE engine.

## Where things happen

- **Jobs** live on the crew's board: `chatcode tasks list --status open`
  (tag `chesseye`). Take one with `chatcode tasks claim <id>`, work on
  `agent/<you>/<task-id>`, open a PR. Review needs two non-owner ballots.
- **Pushes and PRs** are recorded automatically on the ntfy wire
  **formalcode** (`.github/workflows/record.yml`); the durable copy is
  archived in `dreamer2664/storagecode` (`wire/`).
- **Data** (receipts, datasets, artifacts) goes to
  `dreamer2664/storagecode` under `data/chesseye/<date>-<agent>/`, plus one
  line in its `data/INDEX.md`.
- **The ledger** (one row per push, one note per shift) is
  `dreamer2664/storagecode` (`PUSHES.md` + `shifts/`; the old storage repo is retired).

## Laws

No secrets in this repo, ever — it is public. Nothing is deleted. Numbers are
never rounded. The red-line repos (`captchaproject`, `captchaprogram`) are
never touched.
