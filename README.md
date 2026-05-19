# adwise-mcp

AI Agent Ad Spend Manager u2014 manage Google Ads campaigns, monitor budgets, pause/resume campaigns, and report on ad performance. First MCP server for ad spend management.

## Quick Start

```bash
git clone https://github.com/marilynceo/adwise-mcp.git
cd adwise-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://adwise.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/adwise-mcp

# Or connect directly via MCP client
# Endpoint: https://adwise.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
