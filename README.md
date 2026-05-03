# PulseSol

> **See what whales do. Mirror it.**

PulseSol is a Solana mobile app that lets you track the on-chain activity of top wallets ("whales"), explore their token swaps in real time, and copy their trades with one tap — all from your phone.

---

## Features

- **Whale Tracker** — Follow any Solana wallet and get a live feed of their swaps
- **Trending Whales** — Discover top PnL and volume traders powered by Birdeye
- **Copy Trading** — Mirror a whale's swap instantly via Jupiter
- **Token Deep-Dive** — Price charts, market cap, liquidity, risk analysis (mint authority, freeze, top-holder concentration)
- **Portfolio** — View your own wallet balance, token holdings and allocation
- **Non-custodial** — Connects to your existing Solana wallet via Mobile Wallet Adapter; private keys never leave your device

---

## Tech Stack

| Layer | Technology |
|---|---|
| Mobile framework | React Native + Expo SDK 55 |
| Routing | Expo Router |
| Solana RPC | Helius (via edge proxy) |
| Wallet data | Birdeye (via edge proxy) |
| Swap routing | Jupiter API |
| Wallet connection | Mobile Wallet Adapter (`@wallet-ui/react-native-kit`) |
| State / caching | TanStack Query |
| Edge proxy | Vercel Edge Functions |

---

## Legal

- [Terms of Use](./TERMS_OF_USE.md)
- [Privacy Policy](./PRIVACY_POLICY.md)

---
