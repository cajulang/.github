# Caju

**Caju** is a simple, statically typed programming language that compiles to native x86-64
executables (Linux and Windows) and to WebAssembly. Its compiler is written in Caju itself, and so
is everything else here: the libraries, the websites and the applications.

```sh
curl -fsSL https://raw.githubusercontent.com/cajulang/cajulang/main/install.sh | sh
```

Releases are signed; `caju upgrade` installs new versions side by side and `caju upgrade --rollback`
goes back.

Website: [cajulang.com](https://cajulang.com) · Wallet: [wallet.cajulang.com](https://wallet.cajulang.com)

### The language

| Repository | |
|---|---|
| [cajulang](https://github.com/cajulang/cajulang) | the language: compiler, standard library (with HTTP, WebSocket and TLS 1.3/1.2), test runner, package manager, MCP server |

### Libraries

| Repository | |
|---|---|
| [ui](https://github.com/cajulang/ui) | React-style UI: components in JSX-like syntax, WebAssembly in a worker, hot reload, server-side rendering, browser wallets |
| [web](https://github.com/cajulang/web) | a Gin-style web framework: routes, middlewares, JSON, WebSocket, several processes |
| [fetch](https://github.com/cajulang/fetch) | an HTTP client for the browser and the server, with a `use_request` hook and server-side rendering |
| [web3](https://github.com/cajulang/web3) | Ethereum and EVM chains in the spirit of viem: ABI, accounts and signatures, RPC, wallets, contracts, ENS, account abstraction |
| [pg](https://github.com/cajulang/pg) | a PostgreSQL client: the wire protocol, SCRAM-SHA-256, TLS, transactions, a pool |
| [caju-style](https://github.com/cajulang/caju-style) | utility-first CSS: Tailwind's vocabulary compiled to readable semantic classes |

### Applications

| Repository | |
|---|---|
| [caju-wallet](https://github.com/cajulang/caju-wallet) | a MetaMask web wallet for EVM chains, [wallet.cajulang.com](https://wallet.cajulang.com): balances, tokens and transfers, all in Caju |
| [caju-shop](https://github.com/cajulang/caju-shop) | an online store with an admin panel, built with Caju's server, UI and database libraries |
| [cajulang-ui-site](https://github.com/cajulang/cajulang-ui-site) | the language's website, [cajulang.com](https://cajulang.com), built in Caju |

Packages install by name: `caju pkg add github.com/cajulang/web3`.
