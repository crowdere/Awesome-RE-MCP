[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# Awesome RE-MCP

A curated list of reverse engineering tools with MCP (Model Context Protocol) servers, enabling AI-assisted analysis and automation.

## Table of Contents

- [IDA Pro](#ida-pro)
- [Ghidra](#ghidra)
- [Other Tools](#other-tools)
- [Presentations and Tutorials](#presentations-and-tutorials)
- [Contributing](#contributing)
- [License](#license)

## IDA Pro

- **[ida-mcp-server](https://github.com/mrexodia/ida-pro-mcp)**: A Model Context Protocol server for IDA Pro that enables AI-assisted reverse engineering. It allows AI models to interact with IDA Pro for tasks like function renaming, decompilation, and binary analysis.
- **[ida-mcp-server-plugin](https://github.com/taida957789/ida-mcp-server-plugin)**: An IDA Pro plugin that serves as an MCP server for AI assistants like Claude and Cursor. It enables remote querying and control of IDA Pro for binary analysis.
- **[mcp-server-idapro](https://github.com/fdrechsler/mcp-server-idapro)**: A TypeScript-based MCP server for IDA Pro, providing tools for binary analysis, script execution, and more.
- **[headless-ida-mcp-server](https://github.com/cnitlrt/headless-ida-mcp-server)**: A headless IDA MCP server for automating reverse engineering tasks without the full IDA Pro interface.

## Ghidra

- **[GhidraMCP](https://github.com/LaurieWired/GhidraMCP)**: A Model Context Protocol server for Ghidra that allows LLMs to autonomously reverse engineer applications. It exposes Ghidra's core functionality to AI models.
- **[reverse-engineering-assistant](https://github.com/cyberkaida/reverse-engineering-assistant)**: An MCP server for reverse engineering tasks in Ghidra, providing a model-agnostic AI assistant.
- **[ghidra-mcp](https://github.com/suidpit/ghidra-mcp)**: Exposes Ghidra functionalities via MCP for AI-powered reverse engineering.

## Other Tools

- **[binaryninja-mcp](https://github.com/MCPPhalanx/binaryninja-mcp)**: An MCP server for Binary Ninja, a binary analysis tool.
- **[Jadx MCP Plugin](https://github.com/mobilehackinglab/Jadx-MCP-Plugin)**: A plugin for Jadx, used for decompiling Android apps, with MCP server access.

## Presentations and Tutorials

- **[Automated AI Reverse Engineering with MCP for IDA and Ghidra](https://www.youtube.com/watch?v=iFxNuk3kxhk)**: A video demonstrating the use of MCP plugins for IDA and Ghidra with live reverse engineering examples.
- **[Using an MCP Server with IDA and VS Code / Roo Code for Vulnerability Research](https://www.youtube.com/watch?v=ZFABxmJTm6Y)**: A video showcasing how to use an MCP server with IDA Pro and VS Code for vulnerability research.
- **[Setting up IDA Pro MCP server for AI assisted reverse engineering](https://www.youtube.com/watch?v=2z4LXyHX6KA)**: A step-by-step guide for integrating MCP servers with IDA Pro.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to suggest new tools or improvements.

## License

This list is released under the [CC0 1.0 Universal](LICENSE) license.
