## GitHub Copilot Chat

- Extension Version: 0.23.2 (prod)
- VS Code: vscode/1.96.3
- OS: Windows

## Network

User Settings:
```json
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 20.87.245.6 (321 ms)
- DNS ipv6 Lookup: Error (6250 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (0 ms)
- Electron fetch (configured): HTTP 200 (8443 ms)
- Node.js https: timed out after 10 seconds
- Node.js fetch: HTTP 200 (8903 ms)
- Helix fetch: timed out after 10 seconds

Connecting to https://api.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 140.82.114.21 (372 ms)
- DNS ipv6 Lookup: Error (14 ms): getaddrinfo ENOTFOUND api.individual.githubcopilot.com
- Proxy URL: None (21 ms)
- Electron fetch (configured): HTTP 200 (324 ms)
- Node.js https: HTTP 200 (6765 ms)
- Node.js fetch: timed out after 10 seconds
- Helix fetch: HTTP 200 (1528 ms)

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).