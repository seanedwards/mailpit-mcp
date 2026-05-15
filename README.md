# Mailpit MCP Server

Model Coding Protocol (MCP) server for Mailpit email testing platform.

## Features

- List and search emails
- Get message details, headers, and source
- Download attachments
- Send test emails
- Tag management
- HTML and link validation
- Spam checking
- Message deletion
- Release messages to external servers
- Chaos testing mode

## Docker

Available on GitHub Container Registry:

```bash
docker pull ghcr.io/seanedwards/mailpit-mcp:edge
```

Configure via environment variables:
- `MAILPIT_URL`: Mailpit API URL (default: http://localhost:8025)
- `MCP_TRANSPORT`: Protocol (default: http)
- `MCP_HTTP_HOST`: Listen host (default: 0.0.0.0)
- `MCP_HTTP_PORT`: Listen port (default: 3000)

