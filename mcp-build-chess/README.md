Install this MCP Server by adding the following JSON code to your JSON config file

```json
{
    "mcpserver":
        "chessserver": {
            "command": "uvx",
            "args": [
                "--from",
                "git+http://192.168.1.100/ai/mcp.git",
                "chess"
            ]
        }
}
```

