# Aether

A responsive frontend concept for a tokenized AI compute marketplace. Includes Home, Marketplace, How it works, Network, Docs and App pages.

## Run locally

```sh
npm install
npm run dev
```

Build with `npm run build`. The site uses client-side routes; configure your static host to serve `index.html` for unknown paths.

## Wallet integration

The App page connects to an injected EVM wallet using `eth_requestAccounts`, listens for account and chain changes, and shows the selected address. It does not request a signature, send a transaction, read token balances, or interact with a contract. Disconnect clears the site's current displayed account; revoke site access within the wallet if desired.

## Product status

Market data, pricing, capacity and network metrics are illustrative. There is no backend, live market, token contract, settlement or GPU provisioning. A production launch needs defined credit terms, verified supply, contracts, backend services, and compliance review.
