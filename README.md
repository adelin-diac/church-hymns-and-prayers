# Sunday Mass Presentation Generator

## Setup

1. Copy `.env.template` to `.env.local` and fill in your values
2. Source the env file:
```bash
source .env.local
```
3. Add the MCP server:
```bash
claude mcp add sunday-mass --url $HYMNS_AND_PRAYERS_MCP_SERVER --header "Authorization: Bearer $HYMNS_AND_PRAYERS_MCP_API_KEY" --scope project
```

## Usage

Open Claude Code and say which hymns to use in order.
