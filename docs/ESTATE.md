# Estate bridge notes (toxicwind fork)

This fork (`toxicwind/muse-cli`) is the estate's canonical MetaAIVM
agent profile. Upstream is `nikships/muse-cli`; history is preserved.

## Protocol cross-reference

The gateway protocol here matches the estate's own
`MetaAiVmClient` (`toxicwind/metaclaw-runtime`, `src/vm/client.js`):

| muse-cli (`src/muse_cli/gateway.py`) | metaclaw-runtime (`src/vm/client.js`) |
|---|---|
| `GATEWAY_HOST = "hatch.metaaivm.com"` | `gatewayHost = "hatch.metaaivm.com"` |
| `wss://<vm-id>.metaaivm.com/` | same VM addressing |
| `Noise_XX_25519_AESGCM_SHA256` | `NoiseXXHandshake` |
| protobuf `hatch.noise.*` envelopes | RPC frame pack/unpack |

## Harvest provenance

Collected 2026-09-30 into `/home/toxic/sovereign/hatch/metaaivm-harvest/`:
GitHub-wide `metaaivm` search — 0 repos, 300 code hits (99 unique repos),
3 issues, 4 PRs. This repo was selected over `kleprevost/muse-mcp`
(MCP for Muse agents) and `giauphan/toolcase-gateway` (Rust LLM proxy)
on stars (27), forks (7), recency (pushed 2026-09-27), and the shipped
`skills/` directory.

## Open work

- [ ] Port the TLS-verification fix (`kleprevost/muse-mcp#1` equivalent)
      for the gateway WebSocket (`nikships/muse-cli#1` upstream).
- [ ] Evaluate `kleprevost/muse-mcp` as a companion MCP surface.
