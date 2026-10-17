<p align="center">
  <a href="https://layerhop.com"><img src="./assets/banner.png" alt="LayerHop — One hop. Go further." width="100%"></a>
</p>

<p align="center">
  <a href="https://layerhop.com"><b>Launch app</b></a> ·
  <a href="https://docs.layerhop.com">Docs</a> ·
  <a href="https://docs.layerhop.com/llms.txt">llms.txt</a> ·
  <a href="mailto:dev@layerhop.com">Contact</a>
</p>

## Hop any token across any layer

LayerHop finds the best route for your swap across chains and protocols, then hands you a transaction to sign in your own wallet.

- **Best route, every time.** Each quote is compared across Jupiter, Relay, deBridge, 0x and LI.FI and ranked by what you actually receive.
- **Fees up front.** The LayerHop fee is shown on every quote, alongside provider fees and estimated gas when they're available.
- **Non-custodial.** We never hold your funds or keys. You review and sign every transaction yourself.
- **EVM ↔ Solana.** Ethereum, Arbitrum, Base, Optimism, BNB Chain, Polygon and Solana, with more on the way.

## For builders

Add cross-chain swaps to your product:

| | |
|---|---|
| **REST API** | `GET /v1/quote` → `POST /v1/orders` → `GET /v1/orders/{provider}/{id}`, plus `/v1/simulate` |
| **Dashboard** | [dashboard.layerhop.com](https://dashboard.layerhop.com): sign in with your wallet, create API keys, see usage, logs and orders |
| **Webhooks** | Signed `order.filled` / `refunded` / `failed` events to your server |
| **SDKs** | TypeScript, React, Python, Go, Rust, plus a `layerhop` CLI |
| **Widget** | One iframe or React component, themeable, with postMessage events |
| **AI agents** | MCP server at `mcp.layerhop.com/mcp`: Claude, ChatGPT and Cursor can quote swaps and hand you a link to sign |
| **Partner fees** | Earn your own fee on top of every swap your users make |

Read the docs at **[docs.layerhop.com](https://docs.layerhop.com)**.

## Security

Found a vulnerability? Email **security@layerhop.com**. Please don't open a public issue.

<sub>LayerHop is an interface to third-party protocols. Swaps carry risk; always check the details before you sign.</sub>
