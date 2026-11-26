# Port Remote MCP Server

Remote MCP Server that securely connects Port.io with your IDE, LLM, or agent platform of choice.

This repository publishes MCP Registry metadata for Port’s regional endpoints (not the servers themselves):

| File | Registry name | Region | Endpoint |
|------|----------------|--------|----------|
| `server.json` | `io.port/Port` | EU | `https://mcp.port.io/v1` |
| `server-us.json` | `io.port/Port-US` | US | `https://mcp.us.port.io/v1` |

Separate registry entries let clients such as GitHub Copilot offer distinct EU and US connectors instead of defaulting to a single multi-remote listing.

## Documentation

For full documentation, setup guides, and usage instructions, visit:

**[Port MCP Documentation](https://docs.port.io/ai-interfaces/port-mcp-server/overview-and-installation)**

## Support

- **Documentation**: [docs.port.io](https://docs.port.io/ai-interfaces/port-mcp-server/overview-and-installation)
- **Issues**: For bugs or feature requests, please contact Port support or open an issue in this repository