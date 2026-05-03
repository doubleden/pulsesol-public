# Privacy Policy

**PulseSol**
_Last updated: May 3, 2025_

---

## 1. Overview

PulseSol ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains what information we collect, how we use it, and your rights regarding your data when you use the PulseSol mobile application ("App").

---

## 2. Information We Do NOT Collect

PulseSol is designed with privacy as a core principle. We do **not** collect or store:

- Private keys or seed phrases
- Passwords or authentication credentials
- Precise geolocation data
- Device identifiers or advertising IDs
- Personal identification information (name, email, phone number)

---

## 3. Information We Collect

### 3.1 Wallet Addresses

When you connect a wallet or add a wallet to track, its **public Solana address** is stored locally on your device using AsyncStorage. This data never leaves your device and is not sent to our servers.

### 3.2 App Settings

Your in-app settings (default swap size, slippage, display preferences) are stored locally on your device only.

### 3.3 On-Chain Data Requests

When you use the App, network requests are made to our edge proxy (hosted on Vercel) which then queries:

- **Helius** — for Solana RPC calls and transaction history
- **Birdeye** — for token prices, portfolio data, and trader analytics
- **Jupiter** — for swap quotes and routing

These requests include public Solana wallet addresses you choose to view. **No personal data is included in these requests.** Our proxy does not log wallet addresses or store request history.

### 3.4 Crash and Error Data

The App does not currently integrate any crash reporting or analytics SDK. No crash data is automatically transmitted.

---

## 4. How We Use Information

The limited data processed by the App is used solely to:

- Display on-chain wallet activity and token data
- Execute swaps you explicitly initiate
- Persist your watchlist and settings between app sessions (locally)

---

## 5. Data Sharing

We do not sell, rent, or share your data with third parties for marketing purposes.

Data may be shared with the following parties only as required to operate the App:

| Party | Purpose | Their Privacy Policy |
|---|---|---|
| Helius | Solana RPC & transaction data | https://helius.dev/privacy |
| Birdeye | Token & trader analytics | https://birdeye.so/privacy |
| Jupiter | Swap routing | https://jup.ag/privacy |
| Vercel | Edge proxy hosting | https://vercel.com/legal/privacy-policy |

All wallet addresses passed to these services are public Solana addresses visible to anyone on the blockchain.

---

## 6. Data Storage and Security

- All user preferences and tracked wallets are stored **locally on your device**
- API keys used to access third-party services are stored exclusively on our Vercel edge proxy and are never included in the app binary
- We use HTTPS for all network communication

---

## 7. Blockchain Data is Public

Please be aware that all Solana blockchain data — including wallet balances, transaction history, and token holdings — is **publicly visible** by anyone. PulseSol simply presents this public data in a readable format. We do not make any private data public.

---

## 8. Children's Privacy

The App is not directed at children under the age of 13. We do not knowingly collect any information from children. If you believe a child has used the App, please contact us.

---

## 9. Your Rights

Since PulseSol stores user data only locally on your device, you can delete all App data at any time by:

- Clearing app data in your device settings
- Uninstalling the App

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. We will notify users by updating the "Last updated" date. Continued use of the App after changes constitutes acceptance of the updated Policy.

---

## 11. Contact

If you have any questions or concerns about this Privacy Policy, please contact us:

**Email:** denis.denisv8701@gmail.com
**App:** PulseSol
**Package:** com.pulsesol.app
