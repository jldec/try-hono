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

![Screenshot 2024-04-28 at 22 40 09](https://github.com/jldec/try-hono/assets/849592/ac446a4a-bf19-4827-8195-d17bcb6f76f2)


### build without deploy
```
# wrangler deploy --dry-run --outdir dist --minify src/index.ts
pnpm pre-ship
```

![Screenshot 2024-04-28 at 23 14 00](https://github.com/jldec/try-hono/assets/849592/2175d3c9-3c48-46b5-96a9-1fd1bf943ac4)

### deploy
```
# wrangler deploy --minify src/index.ts
pnpm ship
```
