# transport-mcp-client

An Elixir MCP client for Taskweft: connect to peer MCP servers, list their tools, and call them by name.

## What it is for

`Taskweft.MCP.Client` connects over stdio or HTTP and reaches the peers declared in configuration. `Taskweft.MCP.PeerBehaviour` is the contract a peer connection implements, so a test can swap in a double.

## Build

```sh
mix deps.get
mix compile
```

## Licence

MIT; see `LICENSE`.
