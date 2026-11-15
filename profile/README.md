<p align="center"><img src="logo.png" alt="imdUSD" width="120" height="120"></p>

# imdUSD

**A dollar stablecoin backed by staked IMD and priced by the IdentityMD agent swarm.** You lock staked IMD (sIMD) in
the vault on Ethereum and borrow imdUSD against it. Collateral prices come from attestations by IdentityMD agent
panels, and each one lands on chain only when a quorum of agents agrees. **INFER** is the protocol's token: protocol
revenue goes to the INFER Treasury, and INFER can be staked as sINFER.

[imdusd.com](https://imdusd.com) · [Docs](https://imdusd.com/docs/) · [About](https://imdusd.com/docs/overview/about/) · [INFER](https://infer.imdusd.com) · [X @imdusd](https://x.com/imdusd) · [DefiLlama](https://defillama.com/protocol/infer)

## Live on Ethereum

| | |
|---|---|
| imdUSD | [`0x61aAF8a992A3143e2B0C9cB0030b9fE702854a25`](https://etherscan.io/token/0x61aAF8a992A3143e2B0C9cB0030b9fE702854a25) |
| Vault | [`0x0b69F8DA8D8cE521d74Ea69a7A3475B77302EF82`](https://etherscan.io/address/0x0b69F8DA8D8cE521d74Ea69a7A3475B77302EF82) |
| INFER | [`0x53d0eA0A685220718Dc6a0a6e4617194C6F37921`](https://etherscan.io/token/0x53d0eA0A685220718Dc6a0a6e4617194C6F37921) |
| Treasury | [`0x6Ac8fF96Fb8DCF5d79A8eF1E59D9AC23f2BD27Bc`](https://etherscan.io/address/0x6Ac8fF96Fb8DCF5d79A8eF1E59D9AC23f2BD27Bc) |

The full list is in [Contracts and addresses](https://imdusd.com/docs/reference/contracts-and-addresses/).

## Repositories

| Repo | What it is |
|---|---|
| [infer-protocol](https://github.com/imdusd/infer-protocol) | The live protocol: vault, swarm price feeds, Treasury, governance, and the imdusd.com site |
| [imdusd-keeper](https://github.com/imdusd/imdusd-keeper) | The keeper: oracle watcher, attestation relayer, liquidator, INFER dripper |
| [imdusd-peg-hook](https://github.com/imdusd/imdusd-peg-hook) | PegFeeHook, the Uniswap v4 dynamic-fee hook on the imdUSD/USDC pool |
| [imdusd-v2-audit](https://github.com/imdusd/imdusd-v2-audit) | imdUSD v2 under public audit, with its [audit history](https://github.com/imdusd/imdusd-v2-audit#audit-history) |
| [imdusd-v2-keeper-audit](https://github.com/imdusd/imdusd-v2-keeper-audit) | The v2 keeper, public audit copy |
| [oracle-coop](https://github.com/imdusd/oracle-coop) | A shared consumer for IdentityMD oracle attestations: verify once, read by many |
| [imdusd-box](https://github.com/imdusd/imdusd-box) | Box: pay for an IdentityMD swarm request in imdUSD |
| [infer-launch](https://github.com/imdusd/infer-launch) | Contracts for the INFER token launch |
| [infer-whitepaper](https://github.com/imdusd/infer-whitepaper) | The INFER whitepaper |
| [imd-skills](https://github.com/imdusd/imd-skills) | Claude Code skills for IdentityMD seats |
| [imdusd-story](https://github.com/imdusd/imdusd-story) | Production material for a short film about imdUSD |

## Reviews

v1 was reviewed thirty times before launch, by IdentityMD swarm audits and in-house reviews
([history](https://imdusd.com/docs/reference/audit-history/)). v2 is in public swarm audit waves
([history](https://github.com/imdusd/imdusd-v2-audit#audit-history)). These are swarm panels and in-house reviews, not
third-party audit firms.
