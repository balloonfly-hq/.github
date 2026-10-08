<div align="center">

## FlyLabs

Provably fair crash games on Stellar

[![repo](https://img.shields.io/badge/github-hackathon-scaffold-stellar-f87171?style=flat-square&logo=github)](https://github.com/balloonfly-hq/hackathon-scaffold-stellar)

</div>

BalloonFly is a multiplayer crash-style betting game where the multiplier climbs until the balloon pops — every round verifiable from published seeds and on-chain state.

### Inside the repo

- **Provably fair rounds** — the server seed is hashed and published before the round, client seeds come from the first three players
- **Rising-multiplier payout** — players cash out at any moment to lock in bet × multiplier
- **Soroban contracts** — Rust compiled to WASM with auto-generated TypeScript bindings

### Links

- Source: https://github.com/balloonfly-hq/hackathon-scaffold-stellar
- Stack: `Soroban` · `Rust` · `React` · `TypeScript` · `Scaffold Stellar`
