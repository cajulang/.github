# Caju

**Caju** is a simple, statically typed programming language that compiles to native x86-64
executables (Linux and Windows) and to WebAssembly. Its compiler is written in Caju itself, and so
is everything else here: the libraries, the websites and the applications.

```sh
curl -fsSL https://raw.githubusercontent.com/cajulang/cajulang/main/install.sh | sh
```

Website: [cajulang.vercel.app](https://cajulang.vercel.app)

| Repository | |
|---|---|
| [cajulang](https://github.com/cajulang/cajulang) | the language: compiler, standard library, test runner, package manager, MCP server |
| [ui](https://github.com/cajulang/ui) | React-style UI: components in JSX-like syntax, WebAssembly in a worker, hot reload, server-side rendering |
| [web](https://github.com/cajulang/web) | a Gin-style web framework: routes, middlewares, JSON, several processes |
| [pg](https://github.com/cajulang/pg) | a PostgreSQL client: the wire protocol, SCRAM-SHA-256, transactions, a pool |
| [caju-style](https://github.com/cajulang/caju-style) | utility-first CSS: Tailwind's vocabulary compiled to readable semantic classes |
| [caju-shop](https://github.com/cajulang/caju-shop) | an online store with an admin panel, built with all of the above |
| [cajulang-ui-site](https://github.com/cajulang/cajulang-ui-site) | the language's website rebuilt in Caju |

Packages install by name: `caju pkg add github.com/cajulang/web`.
