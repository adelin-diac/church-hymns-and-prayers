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

## Resources

- [Hymns & Prayers Database (Google Sheets)](https://docs.google.com/spreadsheets/d/1owHGuV4dTqIB9FWqg7lC7fkfqAF8ucE3OwSbtAtTm_o/edit?gid=0#gid=0)
- [MCP Server on n8n](https://n8n.adelindiac.site/projects/tMjfj0agqJZxJUH0/folders/T4kTR9A6227FcSof/workflows)

## Usage

Open Claude Code and say which hymns to use in order.
