Source:
`https://modelcontextprotocol.info/docs/quickstart/quickstart/`

Add to claude_desktop_config.json:
```[json]
{
  "mcpServers": {
    "weather": {
      "command": "uv",
      "args": [
        "--directory",
        "C:\\PATH\\TO\\PROJECT\\weather-mcp",
        "run",
        "weather"
      ]
    }
  }
}
```

(Windows)
