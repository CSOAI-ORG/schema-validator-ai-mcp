<div align="center">

# Schema Validator Ai MCP

**Schema Validator AI MCP Server**

[![PyPI](https://img.shields.io/pypi/v/meok-schema-validator-ai-mcp)](https://pypi.org/project/meok-schema-validator-ai-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-MCP_Server-purple)](https://meok.ai)

</div>

## Overview

Schema Validator AI MCP Server
JSON Schema validation and generation tools powered by MEOK AI Labs.

## Tools

| Tool | Description |
|------|-------------|
| `validate_json_schema` | Validate JSON data against a JSON Schema. |
| `generate_schema` | Generate a JSON Schema from example JSON data. |
| `convert_openapi` | Extract and convert schemas from an OpenAPI specification. |
| `validate_types` | Validate that JSON data fields match expected types. |

## Installation

```bash
pip install meok-schema-validator-ai-mcp
```

## Usage with Claude Desktop

Add to your Claude Desktop MCP config (`claude_desktop_config.json`):

```json
{
  "mcpServers": {
    "schema-validator-ai": {
      "command": "python",
      "args": ["-m", "meok_schema_validator_ai_mcp.server"]
    }
  }
}
```

## Usage with FastMCP

```python
from mcp.server.fastmcp import FastMCP

# This server exposes 4 tool(s) via MCP
# See server.py for full implementation
```

## License

MIT © [MEOK AI Labs](https://meok.ai)
