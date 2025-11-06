Install this MCP Server by adding the following JSON code to your JSON config file

```json
{
    "mcpserver":
        "chessservergitlab": {
            "command": "uvx",
            "args": [
                "--from",
                "git+http://192.168.1.100/ai/mcp.git",
                "chess"
            ]
        },
        "chessservergithub": {
            "command": "uvx",
            "args": [
                "--from",
                "git+https://github.com/SangHPark/chess-mcp-steve.git",
                "chess"
            ]
        }        
}
```

