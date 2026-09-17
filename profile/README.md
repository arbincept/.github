# Arbitrage Inception
### Open-Source Web3 Trading Infrastructure, Cross-DEX Routing & On-Chain Telemetry

Welcome to the official GitHub organization of **Arbitrage Inception**, a non-custodial decentralized finance protocol and developer tooling ecosystem engineered primarily for **BNB Smart Chain (BSC)** and EVM environments.

**Live Application:** [https://arbitrage-inc.exchange](https://arbitrage-inc.exchange)  
**Protocol Analytics:** [DefiLlama](https://defillama.com/protocol/arbitrage-inc) · [Awesome-Web3](https://github.com/ahmet/awesome-web3#open-source-projects)  
**Community & Updates:** [Telegram](https://t.me/ArbitrageInception) · [X / Twitter (@Arbitrageincept)](https://x.com/Arbitrageincept)

---

## 🏛️ Core Open-Source Systems

<table>
  <thead>
    <tr>
      <th width="35%">Project</th>
      <th width="45%">Description</th>
      <th width="20%">Status & Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <b><a href="https://github.com/arbincept/Arb-Inc-All-in-Dex">Arb-Inc-All-in-Dex</a></b><br/>
        <sub>DEX Aggregator & Cross-Chain Terminal</sub>
      </td>
      <td>
        Production-grade DEX aggregator and Swift cross-chain bridge on BNB Chain. Features sub-second routing, limit orders, PWA client, and real-yield telemetry.
      </td>
      <td>
        <a href="https://defillama.com/protocol/arbitrage-inc"><img src="https://img.shields.io/badge/DeFiLlama-Listed-brightgreen" alt="DeFiLlama" /></a><br/>
        <a href="https://github.com/arbincept/Arb-Inc-All-in-Dex"><img src="https://img.shields.io/github/stars/arbincept/Arb-Inc-All-in-Dex?style=social" alt="Stars" /></a>
      </td>
    </tr>
    <tr>
      <td>
        <b><a href="https://github.com/arbincept/inception-flap-scanner">Inception Flap Scanner</a></b><br/>
        <sub>Security Screener & Bonding Curve Auditor</sub>
      </td>
      <td>
        Real-time on-chain safety analyzer. Evaluates ERC-1167 minimal proxies, bonding curve dynamics, honeypot signatures, and dev wallet distributions.
      </td>
      <td>
        <a href="https://huggingface.co/spaces/Lucace/inception-flap-scanner"><img src="https://img.shields.io/badge/HuggingFace-Live_Space-yellow" alt="HuggingFace" /></a><br/>
        <a href="https://github.com/arbincept/inception-flap-scanner"><img src="https://img.shields.io/github/stars/arbincept/inception-flap-scanner?style=social" alt="Stars" /></a>
      </td>
    </tr>
    <tr>
      <td>
        <b><a href="https://github.com/arbincept/bsc-arbitrage-scanner">bsc-arbitrage-scanner</a></b><br/>
        <sub>High-Throughput Arbitrage Engine</sub>
      </td>
      <td>
        Asynchronous Python telemetry engine simulating multi-hop triangular routing, mempool state updates, and net profitability models across BSC liquidity pools.
      </td>
      <td>
        <img src="https://img.shields.io/badge/Python-3.11_AsyncIO-3776AB?logo=python&logoColor=white" alt="Python" /><br/>
        <a href="https://github.com/arbincept/bsc-arbitrage-scanner"><img src="https://img.shields.io/github/stars/arbincept/bsc-arbitrage-scanner?style=social" alt="Stars" /></a>
      </td>
    </tr>
    <tr>
      <td>
        <b><a href="https://github.com/arbincept/arbitrage-inc-earn">arbitrage-inc-earn</a></b><br/>
        <sub>Composable Lending & Yield Vaults</sub>
      </td>
      <td>
        DeFi vault interface connecting Venus Protocol money markets, Lista DAO liquid staking (slisBNB), and custom real-yield distribution contracts.
      </td>
      <td>
        <img src="https://img.shields.io/badge/BNB_Chain-EVM-F0B90B?logo=binance&logoColor=white" alt="BNB Chain" /><br/>
        <a href="https://github.com/arbincept/arbitrage-inc-earn"><img src="https://img.shields.io/github/stars/arbincept/arbitrage-inc-earn?style=social" alt="Stars" /></a>
      </td>
    </tr>
  </tbody>
</table>

---

## 🛡️ Architecture & Verification Standards

All repositories under **Arbitrage Inception** operate under strict open-source governance:
- **Zero Custody:** Smart contract interactions and swaps occur purely non-custodial via verified decentralized routers (KyberSwap Aggregator, Mayan Finance, PancakeSwap).
- **Automated Security:** Verified with HashDit automated security scanning (**0 issues detected** across all integration checks).
- **Canonical Metrics:** Adapter volumes, fees, and token tax revenue are continuously tracked and verified on [DefiLlama Dimension Adapters](https://github.com/DefiLlama/dimension-adapters).

---

## 👥 Organization & Maintainers

- **Founder & Lead Systems Architect:** [@Lukecele](https://github.com/Lukecele) (Luca Celebrano)
- **Official Organization:** [github.com/arbincept](https://github.com/arbincept)
- **Sponsorship & Support:** [GitHub Sponsors (@Lukecele)](https://github.com/sponsors/Lukecele)
