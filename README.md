# Schema Validator Ai

> By [MEOK AI Labs](https://meok.ai) — MEOK AI Labs MCP Server

Schema Validator AI MCP Server

## Installation

```bash
pip install schema-validator-ai-mcp
```

## Usage

```bash
# Run standalone
python server.py

# Or via MCP
mcp install schema-validator-ai-mcp
```

## Tools

### `validate_json_schema`
Validate JSON data against a JSON Schema.

**Parameters:**
- `data_json` (str)
- `schema_json` (str)

### `generate_schema`
Generate a JSON Schema from example JSON data.

**Parameters:**
- `data_json` (str)
- `title` (str)

### `convert_openapi`
Extract and convert schemas from an OpenAPI specification.

**Parameters:**
- `openapi_json` (str)
- `extract_schemas` (bool)

### `validate_types`
Validate that JSON data fields match expected types.

**Parameters:**
- `data_json` (str)
- `type_spec` (str)


## Authentication

Free tier: 15 calls/day. Upgrade at [meok.ai/pricing](https://meok.ai/pricing) for unlimited access.

## Links

- **Website**: [meok.ai](https://meok.ai)
- **GitHub**: [CSOAI-ORG/schema-validator-ai-mcp](https://github.com/CSOAI-ORG/schema-validator-ai-mcp)
- **PyPI**: [pypi.org/project/schema-validator-ai-mcp](https://pypi.org/project/schema-validator-ai-mcp/)

## License

MIT — MEOK AI Labs
