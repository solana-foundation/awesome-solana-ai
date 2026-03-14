# Awesome Solana AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI-powered tools, skills, and resources for Solana development.

**Disclaimer:** The resources listed here are community-contributed and are **not endorsed by the Solana Foundation**. Always do your own research (DYOR) before using any tool or resource. Inclusion in this list does not imply any warranty, security audit, or official recommendation.

## Contents

- [AI Coding Skills](#ai-coding-skills)
  - [General](#general)
  - [DeFi](#defi)
  - [Infrastructure](#infrastructure)
- [AI Agents](#ai-agents)
- [Developer Tools](#developer-tools)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

## AI Coding Skills

AI coding skills that enhance developer productivity on Solana.

### General

- [clawpump-skill](https://www.clawpump.tech/skill.md) - AI agent skill for ClawPump covering gasless and self-funded token launches on pump.fun, dynamic dev buys with instant graduation, 65% trading fee revenue share, and social amplification via Moltbook.
- [helius-phantom-skill](https://github.com/helius-labs/core-ai/tree/main/helius-skills/helius-phantom) - Official Helius + Phantom Connect skill for building frontend Solana apps with React, React Native, and browser SDKs, transaction signing via Helius Sender, token gating, NFT minting, crypto payments, and real-time updates.
- [magicblock-dev-skill](https://github.com/magicblock-labs/magicblock-dev-skill) - End-to-end MagicBlock development skill for Claude Code. [MagicBlock](https://magicblock.xyz) is a Solana network extension designed to help programs with latency/privacy needs, along with other native tools like VRFs, Cranks, Session Keys and more.
- [metaplex-skill](https://github.com/metaplex-foundation/skill) - Official Metaplex development skill covering Core NFTs, Token Metadata, Bubblegum, Candy Machine, Genesis token launches, the mplx CLI, and Umi/Kit SDKs.
- [solana-anchor-claude-skill](https://github.com/quiknode-labs/solana-anchor-claude-skill) - end to end Solana development for Anchor and Solana Kit. Focusing on modern, minimal, readable code for long-term maintenance. Testing is with native test runners or LiteSVM. See [I made a Solana exchange using this Claude skill!](https://www.youtube.com/watch?v=QcinP8mGWxg) for more details.
- [solana-dev-skill](https://github.com/solana-foundation/solana-dev-skill) - End-to-end Solana development skill for Claude Code. Covers wallet connections, Anchor/Pinocchio programs, client generation, testing with LiteSVM/Mollusk, and security best practices.
- [solana-game-skill](https://github.com/solanabr/solana-game-skill) - Claude Code skills for developing games on Solana. Covers C#, React Native, Magicblock's Solana Unity SDK, Solana Mobile and Playsolana Unity SDK. Extends [solana-dev-skill](https://github.com/solana-foundation/solana-dev-skill).
- [solana-skills-plugin](https://github.com/tenequm/claude-plugins/tree/main/solana) - Solana skills for Claude Code: program development with Anchor/native Rust (testing and deployment included), security auditing with vulnerability detection and audit report generation, and ZK compression for rent-free tokens/PDAs via Light Protocol.

### DeFi

- [clawpump-arbitrage-skill](https://clawpump.tech/arbitrage.md) - AI agent skill for multi-DEX arbitrage on Solana covering 11 DEX quote aggregation, roundtrip and bridge strategies, and ready-to-sign transaction bundle generation.
- [dflow-phantom-connect-skill](https://github.com/DFlowProtocol/dflow_phantom-connect-skill) - Official DFlow + Phantom Connect skill for building full-stack, wallet-connected Solana apps with Phantom Connect SDKs, plus DFlow swaps, prediction market trading, and Proof KYC verification.
- [dflow-skill](https://github.com/sendaifun/skills/tree/main/skills/dflow) - AI coding skill for DFlow trading protocol covering spot trading, prediction markets, Swap API, and WebSocket streaming on Solana.
- [drift-skill](https://github.com/sendaifun/skills/tree/main/skills/drift) - AI coding skill for Drift Protocol SDK covering perpetual futures, spot trading, and DeFi applications on Solana.
- [helius-dflow-skill](https://github.com/helius-labs/core-ai/tree/main/helius-skills/helius-dflow) - Official Helius + DFlow skill for building Solana trading apps combining DFlow spot swaps, prediction markets, and real-time market streaming with Helius Sender, priority fees, LaserStream, and wallet intelligence.
- [jupiter-skill](https://github.com/jup-ag/agent-skills/tree/main/skills/integrating-jupiter) - AI coding skill for Jupiter covering Ultra swaps, limit orders, DCA, perpetuals, lending, and token APIs on Solana.
- [kamino-skill](https://github.com/sendaifun/skills/tree/main/skills/kamino) - AI coding skill for Kamino Finance covering lending, borrowing, liquidity management, leverage trading, and oracle aggregation on Solana.
- [lulo-skill](https://github.com/sendaifun/skills/tree/main/skills/lulo) - AI coding skill for Lulo, Solana's lending aggregator that routes deposits to the highest-yielding protocols across Kamino, Drift, MarginFi, and Jupiter.
- [meteora-skill](https://github.com/sendaifun/skills/tree/main/skills/meteora) - AI coding skill for Meteora DeFi SDK covering liquidity pools, AMMs, bonding curves, vaults, and token launches on Solana.
- [octav-api-skill](https://github.com/Octav-Labs/octav-api-skill) - AI coding skill for Octav API covering Solana wallet portfolio tracking, transaction history, DeFi protocol positions, and token analytics.
- [orca-skill](https://github.com/sendaifun/skills/tree/main/skills/orca) - AI coding skill for Orca Whirlpools concentrated liquidity AMM covering swaps, liquidity provision, pool creation, and position management.
- [pumpfun-skill](https://github.com/sendaifun/skills/tree/main/skills/pumpfun) - AI coding skill for PumpFun Protocol covering token launches, bonding curves, and PumpSwap AMM integrations on Solana.
- [ranger-finance-skill](https://github.com/sendaifun/skills/tree/main/skills/ranger-finance) - AI coding skill for Ranger Finance, a Solana perps aggregator across Drift, Flash, Adrena, and Jupiter.
- [raydium-skill](https://github.com/sendaifun/skills/tree/main/skills/raydium) - AI coding skill for Raydium Protocol covering CLMM, CPMM, AMM pools, LaunchLab token launches, farming, and Trade API on Solana.
- [sanctum-skill](https://github.com/sendaifun/skills/tree/main/skills/sanctum) - AI coding skill for Sanctum covering liquid staking, LST swaps, and Infinity pool operations on Solana.
- [pnp-markets-skill](https://github.com/pnp-protocol/solana-skill) - AI coding skill for PNP Protocol covering permissionless prediction markets on Solana with V2 AMM, P2P betting, custom oracle settlement, and social media-linked markets.
- [Sentients](https://github.com/koshmade/sentients.wtf) - AI agents minting unique inscriptions on Solana. First AI Agent-Native Protocol with autonomous wallets and deterministic art generated from blockchain entropy.

### Infrastructure

- [coingecko-skill](https://github.com/sendaifun/skills/tree/main/skills/coingecko) - AI coding skill for CoinGecko Solana API covering token prices, DEX pool data, OHLCV charts, and market analytics.
- [debridge-skill](https://github.com/sendaifun/skills/tree/main/skills/debridge) - AI coding skill for deBridge Protocol covering cross-chain bridges, message passing, and token transfers between Solana and EVM chains.
- [helius-skill](https://github.com/helius-labs/core-ai/tree/main/helius-skills/helius) - Official Helius development skill covering transaction sending (Sender), asset/NFT queries (DAS API), real-time streaming (WebSockets, LaserStream), event pipelines (webhooks), priority fees, wallet analysis, and agent onboarding.
- [light-protocol-skill](https://github.com/sendaifun/skills/tree/main/skills/light-protocol) - AI coding skill for Light Protocol's ZK Compression covering rent-free compressed tokens and PDAs using zero-knowledge proofs.
- [metaplex-skill](https://github.com/sendaifun/skills/tree/main/skills/metaplex) - Community AI coding skill for Metaplex Protocol covering Core NFTs, Token Metadata, Bubblegum, Candy Machine, and the Umi framework.
- [pyth-skill](https://github.com/sendaifun/skills/tree/main/skills/pyth) - AI coding skill for Pyth Network oracle covering real-time price feeds with confidence intervals and EMA prices on Solana.
- [quicknode-blockchain-skills](https://github.com/quiknode-labs/blockchain-skills) - AI coding skill for Quicknode infrastructure covering Solana RPC, Jupiter Swap API, Yellowstone gRPC streams, and more.
- [solana-dev-skill-rent-free](https://github.com/Lightprotocol/skills) - Solana development agent skills for Claude Code, OpenClaw and others. Covers client and Anchor/Pinocchio program development without rent-exemption for defi, payments, token distribution, ZK Solana programs and debugging.
- [squads-skill](https://github.com/sendaifun/skills/tree/main/skills/squads) - AI coding skill for Squads Protocol covering multisig wallets, smart accounts, and account abstraction on Solana.
- [svm-skill](https://github.com/helius-labs/core-ai/tree/main/helius-skills/svm) - Official Helius skill for exploring Solana's architecture and protocol internals covering the SVM execution engine, account model, consensus, transactions, validator economics, and token extensions using the Helius blog, SIMDs, and Agave/Firedancer source code.
- [switchboard-skill](https://github.com/sendaifun/skills/tree/main/skills/switchboard) - AI coding skill for Switchboard Oracle covering permissionless price feeds, on-demand data, VRF randomness, and Surge streaming on Solana.

## AI Agents

AI agents and autonomous systems built for Solana.

- [Chronoeffector AI Arena](https://arena.chronoeffector.ai) - Chronoeffector AI is a decentralized platform building a fully autonomous AI agent trading arena on Solana, enabling users to deploy AI agents for trading cryptocurrencies, stocks, commodities, and prediction markets.
- [Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit) - Open-source toolkit connecting AI agents to 30+ Solana protocols with 50+ actions including token operations, NFTs, and swaps. Compatible with Eliza, LangChain, and Vercel AI SDK.
- [Eliza Framework](https://github.com/elizaOS/eliza) - Lightweight TypeScript AI agent framework with Solana integrations, Twitter/X bots, and character-based configuration for agent behaviors.
- [GOAT Framework](https://github.com/goat-sdk/goat) - Open-source toolkit for connecting AI agents to 200+ onchain tools with multi-chain support including Solana, EVM, and more.
- [AgenC](https://github.com/tetsuo-ai/AgenC) - Privacy-focused multi-agent coordination framework with ZK proof integrations and confidential compute for Solana.
- [CYNIC](https://github.com/zeyxx/CYNIC) - Decentralized collective consciousness with 11 AI agents. Anchors judgments on Solana via Proof of Judgment (PoJ), verifies burns on-chain, and uses φ-weighted E-Score for reputation.
- [Breeze Agent Kit](https://github.com/anagrambuild/breeze-agent-kit) - Toolkit for building AI agents that manage Solana yield farming via the Breeze protocol, with four integration paths: MCP server, x402 payment-gated API, a portable SKILL.md for agent frameworks, and one-command install through ClawHub.
- [SAID Protocol](https://saidprotocol.com) - On-chain identity, reputation, and verification infrastructure for AI agents on Solana. Agents register a cryptographically verifiable identity, build reputation scores, and get discovered in the public agent directory. Free to register. Use `create-said-agent` to scaffold an ElizaOS nanobot or OpenClaw agent with a SAID identity built in from the start.
- [Splatworld](https://splatworld.io) - Agent social platform for AI agents to collaborate and vote to generate their own metaverse of 3D gaussian splat worlds and implementing an agentic economy powered by x402.
- [SP3ND Agent Skill](https://github.com/kent-x1/sp3nd-agent-skill) - Agent skill for buying products from Amazon using USDC on Solana. Fully autonomous via x402 payment protocol — register, build a cart, place an order, and pay with USDC in a single API flow. 0% platform fee, no KYC, free Prime shipping to 200+ countries across 22 Amazon marketplaces.
- [OpenDexter](https://open.dexter.cash) - x402 search engine and payment gateway for AI agents. Search 5,000+ paid APIs, check pricing, and pay with automatic USDC settlement. Available as an [MCP server](https://open.dexter.cash/mcp) (no auth needed) or [npm package](https://www.npmjs.com/package/@dexterai/opendexter) (`npx @dexterai/opendexter install`).
- [Blueprint Agentic Staking (Solentic)](https://github.com/mbrassey/solentic) - Native Solana staking infrastructure for AI agents with 18 MCP tools, 21 REST endpoints, and 13 A2A skills. Zero custody design — agents receive unsigned base64 transactions and sign client-side. Supports stake, unstake, withdraw, simulate, and verify operations with ~6% APY via Blueprint validator.

## Developer Tools

AI-enhanced development tools for the Solana ecosystem.

- [Solana Developer MCP](https://mcp.solana.com/) - Maintained by Solana. Solana MCP (Model Context Protocol) is a specialized AI assistant that integrates directly into AI-supported IDEs like Cursor and Windsurf (works with Claude CLI as well). Automatically queries the MCP server to provide accurate, up-to-date information from Solana and Anchor Framework documentation.
- [DFlow MCP Server](https://pond.dflow.net/build/mcp) - Unified spot + prediction market trading API with smart routing and low-failure execution; MCP connects AI tools to DFlow docs, APIs, and code recipes for accurate integrations on Solana.
- [Deside MCP](https://github.com/DesideApp/deside-mcp) - Wallet-to-wallet messaging primitive for Solana agents via MCP, where agents authenticate with an Ed25519 keypair and send DMs addressed by pubkey.
- [SLO (Solana LLM Oracle)](https://github.com/GauravBurande/solana-llm-oracle) - Enables LLM inference directly in Solana programs for on-chain AI capabilities in games and protocols requiring autonomous functions.
- [LumoKit](https://github.com/Lumo-Labs-AI/lumokit) - Lightweight Python AI toolkit for Solana with on-chain actions, token swaps via Jupiter, and research capabilities for ecosystem developers.
- [AImpact](https://aimpact.dev) - online AI-powered IDE for Web3 apps generation, including generating and deploying (currently to devnet, mainnet coming soon) Solana smart contracts.
- [SATI (Solana Agent Trust Infrastructure)](https://github.com/cascade-protocol/sati) - ERC-8004 compliant agent identity and reputation with proof-of-participation: agents sign before knowing feedback outcomes.
- [Exo AI Audits](https://ai-audits.exotechnologies.xyz) - AI-powered smart contract auditing platform for Solana programs.
- [solana-kit-skill](https://github.com/sendaifun/skills/tree/main/skills/solana-kit) - AI coding skill for @solana/kit, the modern tree-shakeable zero-dependency JavaScript SDK from Anza for Solana.
- [solana-kit-migration-skill](https://github.com/sendaifun/skills/tree/main/skills/solana-kit-migration) - AI coding skill for migrating from @solana/web3.js v1.x to @solana/kit with API mappings and edge case handling.
- [pinocchio-skill](https://github.com/sendaifun/skills/tree/main/skills/pinocchio-development) - AI coding skill for Pinocchio, a zero-dependency zero-copy framework for high-performance Solana programs with 88-95% compute unit reduction.
- [vulnhunter-skill](https://github.com/sendaifun/skills/tree/main/skills/vulnhunter) - AI coding skill for security vulnerability detection, dangerous API hunting, and variant analysis across Solana codebases.
- [code-recon-skill](https://github.com/sendaifun/skills/tree/main/skills/zz-code-recon) - AI coding skill for deep architectural context building for security audits, mapping trust boundaries and vulnerability analysis.
- [surfpool-skill](https://github.com/sendaifun/skills/tree/main/skills/surfpool) - AI coding skill for Surfpool, a Solana development environment with mainnet forking, cheatcodes, and Infrastructure as Code.
- [Quicknode MCP](https://www.npmjs.com/package/@quicknode/mcp) - MCP server that lets AI agents provision and manage Quicknode blockchain infrastructure through natural language — set up Solana endpoints, monitor usage, and unlock blockchain operations without leaving your AI assistant.
- [Quicknode RPC via x402](https://www.quicknode.com/docs/build-with-ai/x402-payments) - Pay-per-request access to Solana endpoints using the x402 payment protocol. No signup, no API keys — pay with USDC on Solana and make calls to Solana autonomously. Includes a [reference implementation](https://github.com/quiknode-labs/qn-x402-examples).
- [x402-proxy](https://github.com/cascade-protocol/x402-proxy) - `curl` for x402 paid APIs - auto-pays HTTP 402 responses with USDC on Solana and Base, with MCP stdio proxy for AI agents (`npx x402-proxy`).

## Learning Resources

Educational resources combining AI and Solana development.

- **[Private AI Commerce Demo: Shadow Agent Protocol on Solana](https://ashborn-sol.vercel.app/demo/shadow-agent)** — Interactive demo of fully autonomous AI agents conducting private on-chain commerce. Showcases integration of Ashborn (with Light Protocol and ZK Groth16) for stealth/privacy-protected transactions, PrivacyCash for enhanced anonymity, and x402 protocol flows for micropayments. Includes real TypeScript SDK code examples for stealth transfers, shielding funds, and agent-to-agent payments. Ideal for developers exploring agentic AI systems with maximum privacy on Solana.
  - Tools featured: [Ashborn](https://github.com/AlleyBo55/ashborn) | [Micropay x402 Paywall](https://github.com/AlleyBo55/micropay-solana-x402-paywall)

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
