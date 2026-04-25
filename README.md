# @gandazgul/plannotator-pi-extension-compiled

Compiled wrapper around `@plannotator/pi-extension` so it can be consumed from Deno (which cannot directly use the upstream TypeScript-only package from `node_modules`).

Exports:
- `@gandazgul/plannotator-pi-extension-compiled`
- `@gandazgul/plannotator-pi-extension-compiled/server`
- `@gandazgul/plannotator-pi-extension-compiled/assets` (`plannotatorHtml` string export)

## Build

```bash
npm ci
npm run build
```

## Publish

Publishing is handled by GitHub Actions on tags matching `v*`.
