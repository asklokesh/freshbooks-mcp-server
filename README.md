# FreshBooks MCP Server

A Model Context Protocol (MCP) server for integrating FreshBooks with GenAI applications.

## Overview

Small business accounting software

## Features

- Comprehensive FreshBooks API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install freshbooks-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/freshbooks-mcp-server.git
cd freshbooks-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to FreshBooks API requirements.

## Quick Start

```python
from freshbooks_mcp import FreshbooksMCPServer

# Initialize the server
server = FreshbooksMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
