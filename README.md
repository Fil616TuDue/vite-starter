# vite-starter

Getting started with pnpm/npm/yarn create:

```
# npm
npm create @vlcn.io@latest your-app-name
# pnpm
pnpm create @vlcn.io your-app-name
# yarn
yarn create @vlcn.io your-app-name
```

Or, just cloning directly:

```
git clone git@github.com:vlcn-io/vite-starter.git
npm install
npm dev
```

What you get:
- A client ([App.tsx](https://github.com/vlcn-io/vite-starter/blob/main/src/App.tsx)) that runs a SQLite DB
- A server ([server.js](https://github.com/vlcn-io/vite-starter/blob/main/server.js)) that the client (or many clients) can sync to when onlin devices.
