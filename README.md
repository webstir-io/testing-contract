# @webstir-io/testing-contract

Canonical TypeScript definitions and JSON Schemas for the Webstir testing runtime. Consumers use this package to validate manifests and event payloads emitted by `webstir-test` or alternative runners.

## Install

```bash
npm install @webstir-io/testing-contract
```

## Development

```bash
npm ci
npm run build
npm test
```

## Scripts

| Command        | Description                               |
| -------------- | ----------------------------------------- |
| `npm run build` | Compile TypeScript and emit schemas.       |
| `npm test`      | Build and run validation tests.            |
| `npm run clean` | Remove build artifacts.                    |

## License

MIT © Electric Coding LLC and contributors
