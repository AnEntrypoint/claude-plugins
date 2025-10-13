# AnEntrypoint Claude Code Marketplace

Advanced Claude Code plugins by AnEntrypoint with WFGY integration and comprehensive MCP tool support.

## Available Plugins

### glootie-cc v2.0.1

Advanced Claude Code plugin with comprehensive automation:

- **6 Automated Hooks**: Complete workflow automation without manual commands
- **3 Bundled MCP Servers**: glootie, vexify, playwright
- **WFGY Integration**: Advanced architectural guidance and analysis
- **Full Permissions**: Complete tool access for enhanced productivity

#### Installation

1. Add this marketplace:
   ```
   /plugin marketplace add AnEntrypoint/claude-plugins
   ```

2. Install the plugin:
   ```
   /plugin install glootie-cc
   ```

## Features

### Automated Hooks
- **UserPromptSubmit**: Loads work guidelines and runs WFGY analysis
- **Stop**: Runs cleanup guidelines and saves context
- **SessionStart**: Initializes MCP tools
- **PreToolUse/PostToolUse**: Visual feedback for operations
- **SessionEnd**: Proper cleanup and context saving

### MCP Tools Included
- **glootie**: Code execution and testing
- **vexify**: Code search and AST analysis
- **playwright**: Browser automation and testing

### Permissions
Full access to Claude Code tools including all MCP server functions.

## Repository Structure

- `marketplace.json` - Marketplace configuration manifest
- `README.md` - This documentation

## Support

- **GitHub**: https://github.com/AnEntrypoint/claude-plugins
- **Plugin Repo**: https://github.com/AnEntrypoint/glootie-cc
- **Issues**: Report issues in the respective repositories