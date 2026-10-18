<p align="center">
  <a href="https://layerhop.com"><img src="./assets/banner.png" alt="LayerHop — One hop. Go further." width="100%"></a>
</p>

<p align="center">
  <a href="https://layerhop.com"><b>Launch app</b></a> ·
  <a href="https://docs.layerhop.com">Docs</a> ·
  <a href="https://t.me/layerhop_bot">Telegram bot</a> ·
  <a href="https://dashboard.layerhop.com">Dashboard</a> ·
  <a href="https://docs.layerhop.com/llms.txt">llms.txt</a> ·
  <a href="mailto:dev@layerhop.com">Contact</a>
</p>

## Hop any token across any layer

LayerHop finds the best route for your swap across chains and protocols, then hands you a transaction to sign in your own wallet.

- **Best route, every time.** Each quote is compared across Jupiter, Relay, deBridge, LI.FI, 0x and KyberSwap and ranked by what you actually receive.
- **Fees up front.** The LayerHop fee is shown on every quote, alongside provider fees and estimated gas when they're available.
- **Non-custodial.** We never hold your funds or keys. You review and sign every transaction yourself.
- **70 chains, EVM ↔ Solana.** Ethereum, Base, Arbitrum, Optimism, BNB Chain, Polygon, Solana, Avalanche, Berachain, HyperEVM, Monad and [58 more](https://layerhop.com/chains).

## For builders

Add cross-chain swaps to your product:

| | |
|---|---|
| **REST API** | `GET /v1/quote` → `POST /v1/orders` → `GET /v1/orders/{provider}/{id}`, plus `/v1/simulate` |
| **Dashboard** | [dashboard.layerhop.com](https://dashboard.layerhop.com): sign in with your wallet, create API keys, see usage, logs and orders |
| **Webhooks** | Signed `order.filled` / `refunded` / `failed` events to your server |
| **SDKs** | TypeScript, React, Python, Go, Rust, plus a `layerhop` CLI (see install below) |
| **Widget** | One iframe or React component, themeable, with postMessage events |
| **AI agents** | MCP server at `mcp.layerhop.com/mcp`: Claude, ChatGPT and Cursor can quote swaps and hand you a link to sign |
| **Partner fees** | Earn your own fee on top of every swap your users make |

### Install

```bash
npm install @layerhop/sdk          # TypeScript / JavaScript
npm install @layerhop/react        # React hooks
npm install @layerhop/widget       # embeddable swap widget
npx @layerhop/cli chains           # CLI
npx -y @layerhop/mcp               # MCP server for AI agents
pip install layerhop               # Python
```

| Package | Registry |
|---|---|
| `@layerhop/sdk` | [![npm](https://img.shields.io/npm/v/@layerhop/sdk?color=c3f06b&labelColor=090d15)](https://www.npmjs.com/package/@layerhop/sdk) |
| `@layerhop/react` | [![npm](https://img.shields.io/npm/v/@layerhop/react?color=c3f06b&labelColor=090d15)](https://www.npmjs.com/package/@layerhop/react) |
| `@layerhop/widget` | [![npm](https://img.shields.io/npm/v/@layerhop/widget?color=c3f06b&labelColor=090d15)](https://www.npmjs.com/package/@layerhop/widget) |
| `@layerhop/cli` | [![npm](https://img.shields.io/npm/v/@layerhop/cli?color=c3f06b&labelColor=090d15)](https://www.npmjs.com/package/@layerhop/cli) |
| `@layerhop/mcp` | [![npm](https://img.shields.io/npm/v/@layerhop/mcp?color=c3f06b&labelColor=090d15)](https://www.npmjs.com/package/@layerhop/mcp) |
| `layerhop` (Python) | [![PyPI](https://img.shields.io/pypi/v/layerhop?color=c3f06b&labelColor=090d15)](https://pypi.org/project/layerhop/) |

## Open-source repositories

| Repository | What's inside |
|---|---|
| [layerhop-js](https://github.com/layerhop/layerhop-js) | TypeScript SDK, React hooks, swap widget, CLI and MCP server (MIT) |
| [layerhop-python](https://github.com/layerhop/layerhop-python) | Python SDK, sync + async (MIT) |

Read the docs at **[docs.layerhop.com](https://docs.layerhop.com)**. Questions? See [SUPPORT.md](https://github.com/layerhop/.github/blob/main/SUPPORT.md).

## Security

Found a vulnerability? Email **security@layerhop.com**. Please don't open a public issue.

<sub>LayerHop is an interface to third-party protocols. Swaps carry risk; always check the details before you sign.</sub>
