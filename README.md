# Sunday Mass Presentation Generator

## Setup

1. Copy `.env.example` to `.env` and fill in your values
2. Source the env file:
```bash
source .env
```
3. Add the MCP server:
```bash
claude mcp add sunday-mass --url $MCP_SERVER_URL --header "Authorization: Bearer $MCP_API_KEY" --scope project
```

## Usage

Open Claude Code and say which hymns to use in order.
