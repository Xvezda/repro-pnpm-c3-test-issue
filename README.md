# repro-pnpm-c3-test-issue

This repository is created by following commands:

```sh
pnpm create cloudflare@latest repro-pnpm-c3-test-issue --type=hello-world --deploy=false --ts --git
```

## Solution

```sh
pnpm update wrangler @cloudflare/vitest-pool-workers @cloudflare/workers-types
```

See [cloudlfare/workers-sdk#5311](https://github.com/cloudflare/workers-sdk/issues/5311) for more details.
