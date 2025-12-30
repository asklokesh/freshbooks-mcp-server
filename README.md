# FreshBooks MCP Server

<!-- mcp-name: io.github.asklokesh/freshbooks-mcp-server -->

<div align="center">

# Freshbooks Mcp Server

[![GitHub stars](https://img.shields.io/github/stars/LokiMCPUniverse/freshbooks-mcp-server?style=social)](https://github.com/LokiMCPUniverse/freshbooks-mcp-server/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/LokiMCPUniverse/freshbooks-mcp-server?style=social)](https://github.com/LokiMCPUniverse/freshbooks-mcp-server/network)
[![GitHub watchers](https://img.shields.io/github/watchers/LokiMCPUniverse/freshbooks-mcp-server?style=social)](https://github.com/LokiMCPUniverse/freshbooks-mcp-server/watchers)

[![License](https://img.shields.io/github/license/LokiMCPUniverse/freshbooks-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/freshbooks-mcp-server/blob/main/LICENSE)
[![Issues](https://img.shields.io/github/issues/LokiMCPUniverse/freshbooks-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/freshbooks-mcp-server/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/LokiMCPUniverse/freshbooks-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/freshbooks-mcp-server/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/LokiMCPUniverse/freshbooks-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/freshbooks-mcp-server/commits)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-DC143C?style=for-the-badge)](https://modelcontextprotocol.io)

[![Commit Activity](https://img.shields.io/github/commit-activity/m/LokiMCPUniverse/freshbooks-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/freshbooks-mcp-server/pulse)
[![Code Size](https://img.shields.io/github/languages/code-size/LokiMCPUniverse/freshbooks-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/freshbooks-mcp-server)
[![Contributors](https://img.shields.io/github/contributors/LokiMCPUniverse/freshbooks-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/freshbooks-mcp-server/graphs/contributors)

</div>

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
