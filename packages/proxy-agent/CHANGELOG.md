# proxy-agent

## 6.5.0

### Minor Changes

- 85b10b3: Lazily load agents in proxy-agent
- 96b771b: Include ClientRequest in getProxyForUrl parameters for additional flexibility

### Patch Changes

- ad68f63: Dispose of Agent instances in cache correctly
- Updated dependencies [38760db]
- Updated dependencies [77c3599]
- Updated dependencies [913a49a]
- Updated dependencies [1699a09]
- Updated dependencies [e90e2b2]
  - pac-proxy-agent@7.1.0
  - https-proxy-agent@7.0.6
  - socks-proxy-agent@8.0.5
  - agent-base@7.1.2

## 6.4.0

### Minor Changes

- e7e0e56: Allow `getProxyForUrl()` option to return a Promise

### Patch Changes

- Updated dependencies [c3c405e]
  - http-proxy-agent@7.0.1
  - https-proxy-agent@7.0.3

## 6.3.1

### Patch Changes

- 1d39f6c: Fix Electron support by using Node.js native URL object
- Updated dependencies [1d39f6c]
- Updated dependencies [e625d10]
  - socks-proxy-agent@8.0.2
  - pac-proxy-agent@7.0.1
  - https-proxy-agent@7.0.2

## 6.3.0

### Minor Changes

- f1f3220: Use QuickJS version of `pac-proxy-agent`

### Patch Changes

- Updated dependencies [f1f3220]
  - pac-proxy-agent@7.0.0

## 6.2.2

### Patch Changes

- 999dd9d: Fix `pac+` prefixed protocol URIs
- Updated dependencies [999dd9d]
  - pac-proxy-agent@6.0.4

## 6.2.1

### Patch Changes

- 4a45593: Fix WebSocket connections over "http"/"https" proxies
- Updated dependencies [b3860aa]
  - https-proxy-agent@7.0.0
  - http-proxy-agent@7.0.0
  - pac-proxy-agent@6.0.3

## 6.2.0

### Minor Changes

- 0bbe335: Support for `getProxyForUrl` option, to provide proxy address dynamically per different URLs

### Patch Changes

- Updated dependencies [bf20b04]
  - pac-proxy-agent@6.0.2

## 6.1.2

### Patch Changes

- 7674748: Update `@types/node` to v14.18.45
- Updated dependencies [fd6209c]
- Updated dependencies [c573dbe]
- Updated dependencies [7674748]
  - https-proxy-agent@6.1.0
  - socks-proxy-agent@8.0.1
  - http-proxy-agent@6.0.1
  - pac-proxy-agent@6.0.1
  - agent-base@7.0.1

## 6.1.1

### Patch Changes

- f30ed32: Use `HttpProxyAgent` for "http" and `HttpsProxyAgent` for "https"

## 6.1.0

### Minor Changes

- 9a90063: Add support for `httpAgent` and `httpsAgent` options

## 6.0.0

### Major Changes

- d99a7c8: Major version bump for all packages

### Minor Changes

- 4333067: Add support for core `keepAlive: true`

### Patch Changes

- c169ced: Convert mocha tests to jest for all packages
- Updated dependencies [c169ced]
- Updated dependencies [d99a7c8]
- Updated dependencies [4333067]
- Updated dependencies [06775a8]
  - https-proxy-agent@6.0.0
  - socks-proxy-agent@8.0.0
  - http-proxy-agent@6.0.0
  - pac-proxy-agent@6.0.0
  - agent-base@7.0.0
