[update-readmes]   Mode: rewrite — migrating to template structure...
# binex

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/binex)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/binex.git
cd binex
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration


Binex can be configured via environment variables:

| Variable | Default | Description |
|----------|---------|-------------|
| `BINEX_STORE_PATH` | `.binex` | Directory for SQLite database and artifacts |
| `BINEX_DEFAULT_DEADLINE_MS` | `120000` | Default node timeout in milliseconds |
| `BINEX_DEFAULT_MAX_RETRIES` | `1` | Default retry count for failed nodes |
| `BINEX_DEFAULT_BACKOFF` | `exponential` | Retry backoff strategy (`fixed` or `exponential`) |
| `BINEX_REGISTRY_URL` | `http://localhost:8000` | Default A2A agent registry URL |

All data is stored in `.binex/` (gitignored by default):
- `.binex/binex.db` — SQLite database (runs, execution records, cost records)
- `.binex/artifacts/` — JSON artifact files

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/binex`](https://github.com/Interested-Deving-1896/binex) and mirrored through:

```
Interested-Deving-1896/binex  ──►  OpenOS-Project-OSP/binex  ──►  OpenOS-Project-Ecosystem-OOC/binex
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/binex/blob/master/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
