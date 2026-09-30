# Specter Demo Wallet

A single-file, mobile-style crypto wallet **mockup** with fully editable, fictional balances.
No build step, no dependencies, no network calls.

## Run

Open `index.html` in any browser (on a phone, add it to the home screen for an app-like feel), or:

```
cd demo-wallet && python3 -m http.server 8000
```

## What you can do

- Tap any token (SOL, USDT, USDC, ETH, BTC, BONK, JUP) to edit its **balance, price and 24h change**
- Add your own tokens, remove tokens
- Send / Swap / Buy update balances and log to Activity
- Hide-balance toggle, account name/address editing, "simulate market move"
- Everything persists in the browser's `localStorage`

## Note

This is a simulation. It holds no keys, connects to no blockchain and moves no real funds.
Don't present the balances as real to anyone in a context where it could be relied on
(lending, selling, "proof of funds", etc.) — that's fraud.
