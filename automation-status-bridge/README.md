# Automation Status Bridge

Declares the local Smithery Uplink MCP endpoint (`https://mcp.smithery.run/xandeq/trend-cache`)
so a Claude Code cloud routine cloning this repo can auto-load it via project-scoped `.mcp.json`,
without needing the claude.ai custom-connector OAuth flow.

Exposes: `get_trend_cache(brand)`, `get_windows_tasks_status()`, `get_vps_status()`,
`get_automation_status()`. Full source: `D:\claude-code\_uplink-mcp\` on the notebook.
