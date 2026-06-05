# Excel MCP Server - Virtual Environment Setup

## Overview
This document describes the Python virtual environment setup for the Excel MCP Server, including installation details, activation instructions, and dependency information.

## Environment Details

### Python Version
- **Required:** Python 3.10+
- **Installed:** Python 3.12.3
- **Location:** System Python at `/usr/bin/python3`

### Virtual Environment
- **Location:** `./venv/` (relative to this directory)
- **Full Path:** `/home/dougw/dev/atlas/skills/agent_infrastructure/mcp-servers/excel-mcp-server/venv`
- **Created:** 2026-06-01
- **Python Version in venv:** 3.12.3

## Activation & Deactivation

### Activate Virtual Environment
```bash
# From the excel-mcp-server directory
source venv/bin/activate

# Or using dot notation (POSIX-compatible)
. venv/bin/activate
```

### Deactivate Virtual Environment
```bash
deactivate
```

### Verify Activation
When activated, your shell prompt should be prefixed with `(venv)`:
```bash
(venv) user@host:~/dev/atlas/skills/agent_infrastructure/mcp-servers/excel-mcp-server$
```

## Installed Dependencies

### Core Dependencies (from pyproject.toml)
- **mcp[cli]** >= 1.10.1 (installed: 1.27.2) - Model Context Protocol framework
- **fastmcp** >= 2.0.0, < 3.0.0 (installed: 2.14.7) - Fast MCP server implementation
- **openpyxl** >= 3.1.5 (installed: 3.1.5) - Excel file manipulation library
- **typer** >= 0.16.0 (installed: 0.26.4) - CLI framework

### Complete Package List
The following packages were installed (78 total packages):

| Package | Version | Purpose |
|---------|---------|---------|
| annotated-doc | 0.0.4 | Documentation annotations |
| annotated-types | 0.7.0 | Type annotations |
| anyio | 4.13.0 | Async I/O framework |
| attrs | 26.1.0 | Class attributes |
| Authlib | 1.7.2 | Authentication library |
| beartype | 0.22.9 | Runtime type checking |
| burner-redis | 0.1.7 | Redis utilities |
| cachetools | 7.1.4 | Caching utilities |
| certifi | 2026.5.20 | SSL certificates |
| cffi | 2.0.0 | Foreign function interface |
| click | 8.4.1 | CLI creation kit |
| cloudpickle | 3.1.2 | Serialization |
| cronsim | 2.7 | Cron simulation |
| cryptography | 48.0.0 | Cryptographic recipes |
| cyclopts | 4.16.1 | CLI parsing |
| diskcache | 5.6.3 | Disk-based caching |
| dnspython | 2.8.0 | DNS toolkit |
| docstring_parser | 0.18.0 | Docstring parsing |
| email-validator | 2.3.0 | Email validation |
| et_xmlfile | 2.0.0 | XML file handling |
| excel-mcp-server | 0.1.8 | **Main package (editable)** |
| exceptiongroup | 1.3.1 | Exception grouping |
| fakeredis | 2.34.1 | Redis mock for testing |
| fastmcp | 2.14.7 | **Core MCP framework** |
| h11 | 0.16.0 | HTTP/1.1 protocol |
| httpcore | 1.0.9 | HTTP core |
| httpx | 0.28.1 | HTTP client |
| httpx-sse | 0.4.3 | Server-sent events |
| idna | 3.17 | Internationalized domain names |
| jaraco.classes | 3.4.0 | Class utilities |
| jaraco.context | 6.1.2 | Context managers |
| jaraco.functools | 4.5.0 | Function utilities |
| jeepney | 0.9.0 | D-Bus interface |
| joserfc | 1.6.8 | JOSE (JWT) implementation |
| jsonref | 1.1.0 | JSON references |
| jsonschema | 4.26.0 | JSON schema validation |
| jsonschema-path | 0.5.0 | JSON schema path utilities |
| jsonschema-specifications | 2025.9.1 | JSON schema specs |
| keyring | 25.7.0 | Keyring services |
| lupa | 2.8 | Lua integration |
| markdown-it-py | 4.2.0 | Markdown parser |
| mcp | 1.27.2 | **Model Context Protocol** |
| mdurl | 0.1.2 | Markdown URL utilities |
| more-itertools | 11.1.0 | Iterator utilities |
| openapi-pydantic | 0.5.1 | OpenAPI models |
| openpyxl | 3.1.5 | **Excel file library** |
| opentelemetry-api | 1.42.1 | Telemetry API |
| packaging | 26.2 | Package utilities |
| pathable | 0.6.0 | Path utilities |
| pathvalidate | 3.3.1 | Path validation |
| pip | 26.1.2 | Package installer |
| platformdirs | 4.10.0 | Platform directories |
| prometheus_client | 0.25.0 | Prometheus metrics |
| py-key-value-aio | 0.3.0 | Async key-value store |
| py-key-value-shared | 0.3.0 | Shared key-value utilities |
| pycparser | 3.0 | C parser |
| pydantic | 2.13.4 | Data validation |
| pydantic_core | 2.46.4 | Pydantic core |
| pydantic-settings | 2.14.1 | Settings management |
| pydocket | 0.21.1 | Docker utilities |
| Pygments | 2.20.0 | Syntax highlighting |
| PyJWT | 2.13.0 | JWT implementation |
| pyperclip | 1.11.0 | Clipboard utilities |
| python-dotenv | 1.2.2 | Environment variables |
| python-json-logger | 4.1.0 | JSON logging |
| python-multipart | 0.0.30 | Multipart form data |
| PyYAML | 6.0.3 | YAML parser |
| redis | 8.0.0 | Redis client |
| referencing | 0.37.0 | JSON reference resolution |
| rich | 15.0.0 | Rich text formatting |
| rich-rst | 2.0.1 | RST rendering |
| rpds-py | 2026.5.1 | Persistent data structures |
| SecretStorage | 3.5.0 | Secret storage |
| shellingham | 1.5.4 | Shell detection |
| sortedcontainers | 2.4.0 | Sorted containers |
| sse-starlette | 3.4.4 | SSE for Starlette |
| starlette | 1.2.1 | ASGI framework |
| typer | 0.26.4 | **CLI framework** |
| typing_extensions | 4.15.0 | Type extensions |
| typing-inspection | 0.4.2 | Type inspection |
| uncalled-for | 0.3.2 | Utilities |
| uvicorn | 0.48.0 | ASGI server |
| websockets | 16.0 | WebSocket implementation |

## Installation Commands

### Initial Setup (Already Completed)
```bash
# Navigate to the excel-mcp-server directory
cd atlas/skills/agent_infrastructure/mcp-servers/excel-mcp-server

# Create virtual environment
python3 -m venv venv

# Activate virtual environment
. venv/bin/activate

# Upgrade pip
pip install --upgrade pip

# Install package in editable mode with all dependencies
pip install -e .
```

### Reinstalling Dependencies
If you need to reinstall dependencies:
```bash
# Activate the virtual environment first
. venv/bin/activate

# Reinstall the package
pip install -e . --force-reinstall
```

### Updating Dependencies
```bash
# Activate the virtual environment
. venv/bin/activate

# Update all packages
pip install --upgrade -e .
```

## Configuration Requirements

### Project Structure
The Excel MCP Server is installed in **editable mode**, meaning changes to the source code in `src/excel_mcp/` will be immediately reflected without reinstalling.

### Entry Point
The package provides a CLI entry point:
```bash
excel-mcp-server
```

This command is available when the virtual environment is activated.

### Environment Variables
Check the main [`README.md`](README.md) for any required environment variables or configuration files.

## Verification

### Check Installation
```bash
# Activate venv
. venv/bin/activate

# Verify excel-mcp-server is installed
pip show excel-mcp-server

# List all installed packages
pip list

# Check if the CLI command is available
which excel-mcp-server
```

### Test Import
```bash
# Activate venv
. venv/bin/activate

# Test Python import
python -c "import excel_mcp; print('Excel MCP imported successfully')"
```

## Troubleshooting

### Virtual Environment Not Activating
- Ensure you're in the correct directory
- Use `. venv/bin/activate` instead of `source venv/bin/activate` for better shell compatibility
- Check that the venv directory exists: `ls -la venv/`

### Package Import Errors
- Verify the virtual environment is activated (check for `(venv)` in prompt)
- Reinstall the package: `pip install -e . --force-reinstall`
- Check Python version: `python --version` (should be 3.12.3)

### Permission Errors
- Ensure you have write permissions in the directory
- Don't use `sudo` with pip inside a virtual environment

### Dependency Conflicts
- The virtual environment is isolated from system packages
- If conflicts occur, recreate the venv:
  ```bash
  deactivate
  rm -rf venv
  python3 -m venv venv
  . venv/bin/activate
  pip install --upgrade pip
  pip install -e .
  ```

## Notes

- **Isolation:** This virtual environment is completely isolated from the system Python and other projects
- **Editable Install:** The package is installed in editable mode (`-e`), so source code changes take effect immediately
- **No Conflicts:** All dependencies are contained within `./venv/` and won't affect other Python projects
- **Git Ignore:** The `venv/` directory should be excluded from version control (already in `.gitignore`)

## Next Steps

1. **Activate the environment:** `. venv/bin/activate`
2. **Review the main README:** Check [`README.md`](README.md) for usage instructions
3. **Review available tools:** Check [`TOOLS.md`](TOOLS.md) for MCP tool documentation
4. **Test the server:** Follow the instructions in the main README to run the server

## Maintenance

### Regular Updates
Periodically update dependencies for security patches:
```bash
. venv/bin/activate
pip install --upgrade pip
pip install --upgrade -e .
```

### Dependency Audit
Check for outdated packages:
```bash
. venv/bin/activate
pip list --outdated
```

---

**Setup Date:** 2026-06-01  
**Python Version:** 3.12.3  
**Package Version:** 0.1.8  
**Total Packages:** 78
