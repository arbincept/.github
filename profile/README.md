# Arbitrage Inception
### Open-Source Web3 Trading Infrastructure · Cross-DEX Routing · On-Chain Telemetry · RWA Arbitrage

**Arbitrage Inception** is a non-custodial decentralized finance protocol and developer tooling ecosystem engineered for **BNB Smart Chain (BSC)** and EVM environments. All repositories are open-source and free to use, copy, or modify.

**Live Application:** [https://arbitrage-inc.exchange](https://arbitrage-inc.exchange)  
**Protocol Analytics:** [DefiLlama](https://defillama.com/protocol/arbitrage-inc) · [Awesome-Web3](https://github.com/ahmet/awesome-web3/blob/main/README.md#L407)  
**Community & Updates:** [Telegram](https://t.me/ArbitrageInception) · [X / Twitter (@Arbitrageincept)](https://x.com/Arbitrageincept)

---

## 🏛️ Core Open-Source Systems

<table>
  <thead>
    <tr>
      <th width="25%">Project</th>
      <th width="45%">Architecture & Description</th>
      <th width="30%">Status & Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Arb-Inc All-in-Dex</b><br/><sub>DEX Aggregator & Cross-Chain Terminal</sub></td>
      <td>
        Live open-source DEX aggregator and cross-chain bridge on BNB Chain. Features KyberSwap-powered routing, Mayan Finance cross-chain swaps, limit orders, PWA client, and public real-yield telemetry indexed by DefiLlama.
      </td>
      <td>
        <a href="https://arbitrage-inc.exchange">Live Application</a> ·
        <a href="https://github.com/arbincept/Arb-Inc-All-in-Dex">GitHub</a> ·
        <a href="https://defillama.com/protocol/arbitrage-inc">DefiLlama Analytics</a> ·
        <i>Next.js · TypeScript · Solidity</i>
      </td>
    </tr>
    <tr>
      <td><b>Inception Flap Scanner</b><br/><sub>Security Screener & Bonding Curve Auditor</sub></td>
      <td>
        Real-time on-chain security screener for BNB Smart Chain. Detects ERC-1167 minimal proxies, honeypot signatures, bonding curve anomalies, and dev wallet distributions. Deployed on HuggingFace Spaces via Docker.
      </td>
      <td>
        <a href="https://lucace-inception-flap-scanner.hf.space">Live Application</a> ·
        <a href="https://github.com/arbincept/inception-flap-scanner">GitHub</a> ·
        <a href="https://github.com/arbincept/inception-flap-scanner/releases/tag/v1.1.0">v1.1.0 Release</a> ·
        <i>React · Docker · HuggingFace</i>
      </td>
    </tr>
    <tr>
      <td><b>Arbitrage Inc Earn</b><br/><sub>Composable Lending & Yield Vaults</sub></td>
      <td>
        DeFi vault interface connecting Venus Protocol money markets, Lista DAO liquid staking (slisBNB), Stader, and pSTAKE. Custom real-yield distribution contracts with zap routing for single-asset entry.
      </td>
      <td>
        <a href="https://arbitrage-inc-earn.vercel.app">Live Application</a> ·
        <a href="https://github.com/arbincept/arbitrage-inc-earn">GitHub</a> ·
        <i>Next.js · viem · wagmi · BNB Chain</i>
      </td>
    </tr>
    <tr>
      <td><b>BSC Arbitrage Scanner</b><br/><sub>Read-Only Arbitrage & Route Scanner</sub></td>
      <td>
        Python-based read-only route simulation engine on BNB Smart Chain. It consumes live token lists, queries KyberSwap Aggregator routes, checks GoPlus token security and DexScreener liquidity, and models gas, slippage, and token-tax friction before reporting theoretical opportunities.
      </td>
      <td>
        <a href="https://github.com/arbincept/bsc-arbitrage-scanner">GitHub</a> ·
        <a href="https://github.com/arbincept/bsc-arbitrage-scanner/releases/tag/v1.1.0">v1.1.0 Release</a> ·
        <i>Python 3.12 · requests · KyberSwap API</i>
      </td>
    </tr>
    <tr>
      <td><b>RWA Stock Arbitrage Suite</b><br/><sub>Tokenized Equities Spread Engine</sub></td>
      <td>
        Dual arbitrage engine for BNB Chain tokenized stocks (RWA). Identifies market-hours basis divergence (NYSE/NASDAQ close vs 24/7 on-chain price) and cross-protocol spread opportunities between Ondo Finance and bStocks wrappers. Includes MCP server and Binance Wallet Skill adapter for autonomous AI agent execution.
      </td>
      <td>
        <a href="https://rwa-stock-arbitrage.vercel.app">Live Application</a> ·
        <a href="https://github.com/arbincept/rwa-stock-arbitrage">GitHub</a> ·
        <i>React 19 · TypeScript · Vite · MCP · BNB Chain</i>
      </td>
    </tr>
  </tbody>
</table>

---

## 🌐 Open-Source Adoption & Verified Ecosystem Indexing

- **[DefiLlama / dimension-adapters](https://github.com/DefiLlama/dimension-adapters):** Upstream production fee adapters and real yield metrics merged by DefiLlama maintainers ([PR #9453](https://github.com/DefiLlama/dimension-adapters/pull/9453), [PR #6279](https://github.com/DefiLlama/dimension-adapters/pull/6279), [PR #6275](https://github.com/DefiLlama/dimension-adapters/pull/6275)) — live analytics on [DefiLlama Protocol Analytics (ID 7591)](https://defillama.com/protocol/arbitrage-inc).
- **[Awesome-Web3 Directory](https://github.com/ahmet/awesome-web3):** Curated directory inclusion for *Arb-Inc All-in-Dex* ([Open Source Project, Line 407](https://github.com/ahmet/awesome-web3/blob/main/README.md#L407), [PR #796](https://github.com/ahmet/awesome-web3/pull/796)) and *Inception Flap Scanner* ([Risk Management, Line 343](https://github.com/ahmet/awesome-web3/blob/main/README.md#L343), [PR #795](https://github.com/ahmet/awesome-web3/pull/795)).
- **[ethereum-lists/chains](https://github.com/ethereum-lists/chains):** Contribution merged — dRPC endpoints added to Sonic chain registry ([PR #8730](https://github.com/ethereum-lists/chains/pull/8730)), propagated to MetaMask, Chainlist, and EVM tooling globally.
- **Public Repository Activity:** GitHub Traffic Analytics currently reports **1,026 clones / 375 unique cloners** for *Arb-Inc-All-in-Dex*, **413 / 179** for *inception-flap-scanner*, and **211 / 96** for *bsc-arbitrage-scanner*.

#### Ecosystem Submissions (Pending Maintainer Review)
- **[BNB Chain Developer Tooling](https://github.com/bnb-chain/developer-tools-list/pull/98):** Open ecosystem developer-tools submission; HashDit reported no serious issues in an automated scan. The PR remains open and the scan is not a manual audit.
- **[BNB Chain Awesome Catalog](https://github.com/bnb-chain/awesome/pull/16):** Open curated BNB Smart Chain ecosystem-tools submission; HashDit reported no serious issues in an automated scan.

---

## 🛡️ Architecture & Non-Custodial Notice

- **Zero Custody:** All smart contract interactions occur non-custodially via verified decentralized routers (KyberSwap Aggregator, Mayan Finance, PancakeSwap). No repository holds or controls user funds.
- **Automated Security:** HashDit automated scanning reported no serious issues in referenced integration checks. This does not replace a manual security audit.
- **Open Metrics:** Adapter volumes, fees, and token tax revenue are publicly tracked via [DefiLlama Dimension Adapters](https://github.com/DefiLlama/dimension-adapters).

---

## 👥 Organization & Maintainers

- **Founder & Lead Systems Architect:** [@Lukecele](https://github.com/Lukecele) (Luca Celebrano)
- **Official Organization:** [github.com/arbincept](https://github.com/arbincept)
- **Sponsorship & Support:** [GitHub Sponsors (@Lukecele)](https://github.com/sponsors/Lukecele)

---

### ⭐ Open-Source Support

If you find any of these repositories, architecture models, or on-chain telemetry engines helpful in your work or research, please consider leaving a **Star** on the respective projects. Your feedback and support help drive continuous open-source development and ecosystem maintenance!
