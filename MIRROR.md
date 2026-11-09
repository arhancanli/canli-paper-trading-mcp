# Where this code lives

This repository is the standalone home of the `canli-paper-trading-mcp` package, published so the server can be installed, scanned
and reviewed on its own. It is imported from the `mcp-paper/` directory of
[arhancanli/canlicapital](https://github.com/arhancanli/canlicapital/tree/main/mcp-paper), which is where changes are
made and tested; this repository is updated from it at each release.

Imported from canlicapital commit `61064fe3ebaf74587a3e9694a357084aaf7da1e0` (tag `paper-mcp-v0.3.1`).

- npm: https://www.npmjs.com/package/canli-paper-trading-mcp
- MCP Registry: `io.github.arhancanli/canli-paper-trading-mcp`
- All Canli servers in one, five tools in context: `npx -y canli-mcp` (https://www.npmjs.com/package/canli-mcp)
- Local only: it needs your own Alpaca paper keys.
- About it: https://canlicapital.com/mcp-servers/paper-trading

Files owned by this repository and kept across syncs: `.github/` (CI, CodeQL, OpenSSF Scorecard and Dependabot),
`.gitignore`, `MIRROR.md`, `glama.json`, and the digest-pinned base image in `Dockerfile`.
