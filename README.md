# context-mcp

A modular context manager MCP server using Jinja2 for prompt generation.

## Features
- Modular Jinja2 template system
- Organized templates for coding, best practices, and language-specific guidance
- Extensible MCP server foundation

## Usage
1. Place your Jinja2 templates in the appropriate subfolders under `templates/`.
2. Extend the MCP server logic to load and render templates based on user-supplied keywords.
3. Run the server using the provided command (see below).

## Development
- Python 3.13+
- Jinja2
- MCP server SDK

## Resources
- [MCP Protocol](https://modelcontextprotocol.io/llms-full.txt)
- [MCP Python SDK](https://github.com/modelcontextprotocol/create-python-server)

---

This project was bootstrapped using the official MCP server template.