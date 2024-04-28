# Try hono
https://try-hono.jldec.workers.dev/

From https://hono.dev/getting-started/cloudflare-workers

### wrangler
- https://developers.cloudflare.com/workers/wrangler/bundling/
- https://developers.cloudflare.com/workers/wrangler/commands/

### To run and debug locally
```
pnpm install
pnpm dev
```

### Debugging
https://developers.cloudflare.com/workers/testing/debugging-tools/

type 'd' to open Chrome dev tools
or
attach from VS Code with "Wrangler" debug config

### deploy
```
# wrangler deploy --minify src/index.ts
pnpm ship
```
