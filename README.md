# CityJSON Guide Plugin

A comprehensive Claude Code plugin for working with CityJSON (3D city model format). Provides specification access, JavaScript library tutorials, and curated resources.

## Features

- **CityJSON Specification Access** - Query and explore the official CityJSON specification

## Installation

```bash
/plugin marketplace add https://github.com/HideBa/cityjson-plugin

/plugin install cityjson
```

This plugin bundles the `@cityjson/cj-mcp` MCP server for specification access.

### Prerequisites

- Node.js and npm (for MCP server)
- Claude Code with plugin support

### Setup

1. Install the plugin in Claude Code
2. The MCP server (`@cityjson/cj-mcp`) will be automatically started
3. Use slash commands to access features

## Usage

## MCP Server

This plugin integrates the `@cityjson/cj-mcp` MCP server which provides:

- `cityjson_read_spec_outline` - Get specification table of contents
- `cityjson_read_spec_chapter` - Read specific chapters

## Resources

- [CityJSON Official](https://www.cityjson.org/)
- [CityJSON Specification](https://docs.cityjson.org/)
- [JavaScript Libraries](https://www.cityjson.org/extensions/)

## Contributing

This plugin is designed for public distribution. Contributions welcome!

## License

MIT
