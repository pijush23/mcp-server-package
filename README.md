{
  "mcpServers": {
    "airbnb": {
      "command": "npx",
      "args": [
        "-y",
        "@openbnb/mcp-server-airbnb",
        "--ignore-robots-txt"
      ]
    },
    "weathermcp": {
      "command": "uv",
      "args": [
        "--directory",
        "E:\\AgenticAI\\MCP-Presentation\\mcp-server\\01-helloworld",
        "run",
        "weather.py"
      ]
    },
    "LocalNotes": {
      "command": "uv",
      "args": [
        "--directory",
        "E:\\AgenticAI\\MCP-Presentation\\mcp-server\\02-server-readingfile",
        "run",
        "readingfile.py"
      ]
    },
    "ScreenshotDemo": {
      "command": "uv",
      "args": [
        "--directory",
        "E:\\AgenticAI\\MCP-Presentation\\mcp-server\\02-server-readingfile",
        "run",
        "screenshot.py"
      ]
    },
    "Crypto": {
      "command": "uv",
      "args": [
        "--directory",
        "E:\\AgenticAI\\MCP-Presentation\\mcp-server\\03-api-calls",
        "run",
        "crypto.py"
      ]
    },
    "Web Search": {
      "command": "uv",
      "args": [
        "--directory",
        "E:\\AgenticAI\\MCP-Presentation\\mcp-server\\04-model-websearch",
        "run",
        "websearch.py"
      ]
    },
    "Other Inputs": {
      "command": "C:\\Users\\Pijush Kumar Joardar\\.local\\bin\\uv.EXE",
      "args": [
        "run",
        "--directory",
        "E:\\AgenticAI\\MCP-Presentation\\mcp-server\\05-other-input",
        "other_inputs.py"
      ]
    },
    "Prompt": {
      "command": "uv",
      "args": [
        "--directory",
        "E:\\AgenticAI\\MCP-Presentation\\mcp-server\\06-prompt",
        "run",
        "prompt.py"
      ]
    },
    "Resources": {
      "command": "uv",
      "args": [
        "--directory",
        "E:\\AgenticAI\\MCP-Presentation\\mcp-server\\07-resource",
        "run",
        "resources.py"
      ]
    },
    "MCPPackageDownload": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/pijush23/mcp-server-package.git",
        "mcp-server"
      ]
    }
  },
  "preferences": {
    "coworkScheduledTasksEnabled": false,
    "sidebarMode": "chat"
  }
}
