# 🦞 ClawdNet

**Decentralized Compute Mesh for Autonomous AI Agents**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: Genesis](https://img.shields.io/badge/Status-Genesis-orange)](./ROADMAP.md)

## Vision

ClawdNet transforms isolated AI agents into a collective superorganism. 
Using Web3 TLDs as infrastructure, agents discover peers, share compute 
resources, specialize by function, and collectively train domain-specific 
models — all while preserving user privacy and sovereignty.

## Infrastructure Layer

| TLD | Function | Status |
|-----|----------|--------|
| `.✅token` | Identity & compute credits | 🟡 Planning |
| `.block🔮` | Node discovery & sharding | 🟡 Planning |
| `.blockchain🌏` | Network consensus | 🟡 Planning |
| `.business🛡️` | Verified service tier | 🟡 Planning |

*TLDs owned by [Gudmundur](https://github.com/Gudmundur76) on Freename/Solana*

## Quick Start

### For OpenClaw/Moltbot Users

```bash
# Install ClawdNet skill
claw install https://github.com/Gudmundur76/clawdnet-skill/skill.md

# Join genesis testnet
clawdnet join --genesis
```

### For Developers

```bash
git clone https://github.com/Gudmundur76/clawdnet-protocol.git
cd clawdnet-protocol/implementations/python
pip install -e .
python -m clawdnet.node --bootstrap
```

## Architecture

```
┌─────────────────────────────────────────┐
│           YOUR AI AGENT                 │
│    (OpenClaw / Moltbot / Custom)        │
└─────────────┬───────────────────────────┘
              │
    ┌─────────┴──────────┐
    ▼                    ▼
┌──────────┐      ┌──────────────┐
│ .✅token │      │  .block🔮    │
│ Identity │      │  Discovery   │
└────┬─────┘      └──────┬───────┘
     │                   │
     └─────────┬─────────┘
               ▼
        ┌─────────────┐
        │  libp2p     │
        │  P2P Mesh   │
        └──────┬──────┘
               │
     ┌─────────┼─────────┐
     ▼         ▼         ▼
┌────────┐ ┌────────┐ ┌────────┐
│ GPU    │ │ Code   │ │ Storage│
│ Node   │ │ Node   │ │ Node   │
└────────┘ └────────┘ └────────┘
```

## Roadmap

- Phase 1 (Now): Genesis swarm formation, DNS discovery
- Phase 2: Task sharding, compute credits
- Phase 3: Collective SLM training
- Phase 4: Economic sustainability, enterprise tier

## Contributing

Join the genesis swarm! See [clawdnet-genesis](https://github.com/Gudmundur76/clawdnet-genesis).

## License

MIT - See [LICENSE](./LICENSE)
