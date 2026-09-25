<div align="center">

```text
 ██████╗ ██╗  ██╗ ██████╗ ██╗   ██╗ ██████╗ █████╗ ███╗   ██╗
██╔═████╗╚██╗██╔╝██╔═══██╗██║   ██║██╔════╝██╔══██╗████╗  ██║
██║██╔██║ ╚███╔╝ ██║   ██║██║   ██║██║     ███████║██╔██╗ ██║
████╔╝██║ ██╔██╗ ██║   ██║██║   ██║██║     ██╔══██║██║╚██╗██║
╚██████╔╝██╔╝ ██╗╚██████╔╝╚██████╔╝╚██████╗██║  ██║██║ ╚████║
 ╚═════╝ ╚═╝  ╚═╝ ╚═════╝  ╚═════╝  ╚═════╝╚═╝  ╚═╝╚═╝  ╚═══╝
```

**Blockchain · Privacy · Open Hardware · Applied Cryptography · AI Agents**

*Builder, CTO & AI engineer from Cancún, México 🇲🇽 — shipping hardware wallets, private wallets and on-chain agents.*

![Location](https://img.shields.io/badge/Canc%C3%BAn-M%C3%A9xico-0f766e?style=flat-square)
![Hackathons](https://img.shields.io/badge/hackathon%20prizes-10%2B-f59e0b?style=flat-square)
![Ethereum](https://img.shields.io/badge/Ethereum-since%202017-627EEA?style=flat-square&logo=ethereum&logoColor=white)
![Languages](https://img.shields.io/badge/ES%20%C2%B7%20FR%20%C2%B7%20EN-555?style=flat-square)

</div>

---

```console
$ whoami
0xoucan — CTO & AI engineer at the intersection of Ethereum, privacy,
embedded hardware and AI-assisted development.

$ cat focus.txt
→ open-source hardware wallets on ESP32-S3
→ air-gapped QR signing (EIP-4527 / BC-UR)
→ AI agents that execute on-chain
→ developer tooling for EVVM and EIP research
```

In crypto since **2017**, DeFi since **2020**. I like taking an idea from *problem → research → prototype → hardware / software → tested product → open-source docs*, usually on a hackathon clock. Before I wrote code I taught languages and designed courses, so I write repos that a newcomer can actually follow.

I run **FlashTalk Cotorreo** 🍻 — 2-minute flash talks on any blockchain topic, with beers, food, cotorreo y desmadre.

---

## 🔨 Currently building

### 🥬 [LeekWallet](https://github.com/0xOucan/LeekWallet) — build your own hardware wallet
> *lek* — a Yucatec Maya gourd container, made to protect what's inside it.
> **ETHGlobal 2026 Finalist**

Open-source hardware wallet firmware for the **ESP32-S3** and Firefly Pixie. The device decodes calldata itself and **refuses to sign anything it can't show you in full**.

```text
 ┌───────── companion (NOT trusted) ──────────┐        ┌───────────── device (trusted) ─────────────┐
 │ dapp / WalletConnect → ERC-7730 preview    │──tx──▶ │ own decoder → one page per field           │
 │ Tauri desktop · Android · MV3 extension    │◀─sig── │ seed never leaves · signs as shown         │
 └────────────────────────────────────────────┘        └────────────────────────────────────────────┘
        USB CDC  ·  BLE GATT  ·  animated QR (EIP-4527, no cable, no radio)
```

`BIP-39/32/44` · `secp256k1 RFC6979` · `AES-256-GCM vault` · `X25519 + ChaCha20-Poly1305 sessions` · `dice + HW RNG entropy` · `EIP-1559` · `EIP-6963` · `reproducible builds` · `Apache-2.0`

---

## 🏆 Hackathon track record

| Date | Event | Result | Project | Role |
|:--|:--|:--|:--|:--|
| Sep 2026 | ETHGlobal | 🏅 **Finalist** | [LeekWallet](https://github.com/0xOucan/LeekWallet) | CTO · AI engineer |
| Jun 2026 | Fhenix Buildathon | 🥇 **Best Consumer App** | [Z0tz](https://github.com/0xOucan/z0tzLandingPage) | CTO · AI / ZK engineer |
| Oct 2025 | ETHGlobal | 🎣 **Best Use of Fishers** | [PAYVVM](https://github.com/0xOucan/PAYVVM) | CTO · AI engineer |
| Aug 2025 | Monad Mobil3 | 🥉 **3rd — DeFi** | [ACAL](https://github.com/0xOucan/acal-monad-p2p) | CTO · AI engineer |
| Jul 2025 | NapulETH | 🥇 **1st — MVP** | [StuCredi](https://github.com/0xOucan/stucrediNapulETH) | CTO · AI engineer |
| Jul 2025 | Mantle Hackathon | 🥇 **1st place** | [MictlAI: Mantle Quest](https://github.com/0xOucan/MictlAI-MantleQuest) | CTO · AI engineer |
| May 2025 | ETH Cinco de Mayo | 🚀 MVP | [MictlAI](https://github.com/0xOucan/MictlAI) | CTO · AI engineer |
| May 2025 | Celo Proof of Shipping | 🥈 **2nd — Best AI Agent** | [CeloMΔIND](https://github.com/0xOucan/celo-mind-web) | CTO · AI engineer |
| Apr 2025 | Agent Camp | 🥈 **2nd — Best AI Agent** | [Agent XOC](https://github.com/0xOucan/agentexoc) | CTO · AI engineer |
| Mar 2025 | ETHGlobal Trifecta | 🥇 **1st — Coinbase AgentKit** | [ModerIA](https://github.com/0xOucan/ModerIA-AItrifectaethglobal) | AI / back-end engineer |
| Mar 2025 | =nil; Foundation | 🥈 **2nd — Best AI Agent** | [nilAIagent](https://github.com/0xOucan/nilAIagent) | AI engineer |
| Nov 2024 | ETHGlobal | 🔀 Built | [MICTA](https://github.com/ccolorado/micta) — private cross-chain orderbook bridge | Project manager |

**Previously — [EVVM](https://github.com/EVVM-org) (a.k.a. Rollamate):** AI engineer, creator of [EVVM EIP Lab](https://github.com/0xOucan/eiplabv1) (turns any EIP into documented Solidity), creator of Scaffold-EVVM, [LLM-ready docs scraper](https://github.com/0xOucan/evvmdocscrapper) and documentation maintainer.

---

## 🧰 Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=solidity,ts,js,python,c,cpp,bash&perline=7" alt="languages" /><br/>
  <img src="https://skillicons.dev/icons?i=nextjs,react,nodejs,tailwind,graphql,tauri,electron&perline=7" alt="web" /><br/>
  <img src="https://skillicons.dev/icons?i=linux,docker,git,github,vercel,cloudflare,arduino&perline=7" alt="infra" />
</p>

| | |
|:--|:--|
| **Blockchain** | Ethereum · Base · Arbitrum · Monad · Mantle · Celo · Oasis Sapphire · Fhenix CoFHE · Hardhat · Foundry · viem · wagmi · ethers.js · Scaffold-ETH · OpenZeppelin |
| **Standards** | ERC-4337 · EIP-1559 · EIP-4527 · EIP-6963 · ERC-7730 · ERC-5564 / 6538 · WebAuthn · WalletConnect v2 |
| **Protocols** | Circle CCTP · Hyperlane · CoW Protocol · Uniswap v4 hooks · Aave · Chainlink · 0x · MetaMask Delegation · Envio |
| **Crypto** | BIP-39/32/44 · secp256k1 · P-256 · AES-256-GCM · ChaCha20-Poly1305 · X25519 · PBKDF2 · FHE |
| **Embedded** | ESP32-S3 · ESP-IDF · PlatformIO · I²C / SPI · USB · BLE · OLED / TFT · OV5640 · QR decoding |
| **AI** | Coinbase AgentKit · Nebula · multi-agent coding workflows · BYO-key LLM tooling |

---

## 🛠️ Hardware side quests

- 🎮 **[Xbox → Switch adapter](https://github.com/0xOucan/esp32s3n16r8xboxtoswitch)** — ESP32-S3 box with OLED menu: Xbox controller in over BLE, Switch Pro Controller out over USB.
- 🥽 **[DIY FPV goggles](https://github.com/0xOucan/diyfpvgogglesim)** — ESP32-S3 + dual ST7735S displays + Google Cardboard, streams your PC over USB-C at ~25 FPS for FPV simulators.

---

## 🧭 How I build

```text
 test ──▶ fail ──▶ inspect ──▶ understand ──▶ change ──┐
   ▲                                                   │
   └───────────────────────────────────────────────────┘
```

- **Build first** — a working prototype teaches more than a long debate.
- **Privacy is architecture** — hardware, storage, identity, telemetry, UX — from day one.
- **Hardware should be accessible** — commodity parts, open firmware, reproducible builds.
- **AI speeds up the loop**, it doesn't replace the engineering.

**Open to collaborate on:** wallet infrastructure · account abstraction · applied cryptography · open hardware · AI agents · security research.

<div align="center">

```text
       ~ could we build this differently? ~
```

</div>
