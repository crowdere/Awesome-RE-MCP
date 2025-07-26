[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# Awesome RE-MCP

A curated list of reverse engineering tools with MCP (Model Context Protocol) servers, enabling AI-assisted analysis and automation. Help us build the most comprehensive collection by contributing new tools or creating MCP servers for missing categories!

## Table of Contents

- [Disassemblers & Decompilers](#disassemblers--decompilers)
- [Debuggers](#debuggers)
- [Static Analysis Tools](#static-analysis-tools)
- [Dynamic Analysis Tools](#dynamic-analysis-tools)
- [Network Analysis](#network-analysis)
- [Android/Mobile RE Tools](#androidmobile-re-tools)
- [Security Testing Tools](#security-testing-tools)
- [Missing Categories (Need Community Help!)](#missing-categories-need-community-help)
- [Presentations and Tutorials](#presentations-and-tutorials)
- [Getting Started with MCP Development](#getting-started-with-mcp-development)
- [Contributing](#contributing)
- [License](#license)

## Disassemblers & Decompilers

### IDA Pro
- **[ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp)**: Most popular implementation with 20+ tools, automated installation, and streamlined architecture for function analysis and decompilation.
- **[ida-mcp-server](https://github.com/MxIris-Reverse-Engineering/ida-mcp-server)**: Python-based implementation for developers preferring Python integration.
- **[mcp-server-idapro](https://github.com/fdrechsler/mcp-server-idapro)**: TypeScript-based MCP server providing tools for binary analysis and script execution.
- **[ida-mcp-server-plugin](https://github.com/taida957789/ida-mcp-server-plugin)**: IDA Pro plugin with SSE (Server-Sent Events) protocol support for real-time integration with Claude and Cursor.
- **[headless-ida-mcp-server](https://github.com/cnitlrt/headless-ida-mcp-server)**: Headless automation-focused server for CI/CD integration and batch processing.

### Ghidra
- **[GhidraMCP](https://github.com/LaurieWired/GhidraMCP)**: Most comprehensive with 5.4k+ stars, featuring extensive documentation and multi-client support.
- **[reverse-engineering-assistant](https://github.com/cyberkaida/reverse-engineering-assistant)**: AI-first approach with chain-of-reasoning techniques and tool-driven analysis (ReVa).
- **[ghidra-mcp](https://github.com/suidpit/ghidra-mcp)**: Spring Boot enterprise integration for team environments.
- **[GhydraMCP](https://github.com/starsong-consulting/GhydraMCP)**: Multi-headed MCP server supporting multiple Ghidra instances.

### Binary Ninja
- **[binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp)**: Seamless Claude Desktop integration with comprehensive plugin architecture.
- **[binaryninja-mcp](https://github.com/MCPPhalanx/binaryninja-mcp)**: Feature-rich implementation with "superpower" capabilities.
- **[binja_mcp](https://github.com/rsprudencio/binja_mcp)**: Alternative community implementation.
- **[binja-lattice-mcp](https://github.com/Invoke-RE/binja-lattice-mcp)**: Security-focused with token-based authentication and encrypted communication.

### Other Disassemblers
- **[radare2-mcp](https://github.com/radareorg/radare2-mcp)**: Official Radare2 implementation with 26+ tools via STDIO transport.
- **[x64dbgMCP](https://github.com/Wasdubya/x64dbgMCP)**: Exposes 40+ x64dbg SDK tools for Windows debugging.
- **[CutterMCP](https://github.com/ap425q/CutterMCP)**: Rizin-based analysis with modern GUI integration.

## Debuggers

### Full MCP Support
- **[LLDB](https://lldb.llvm.org/use/mcp.html)**: ⭐ Official native MCP support as of June 2025, plus community implementations.
- **[GDB MCP Server](https://www.pulsemcp.com/servers/pansila-gdb)**: Multiple implementations providing comprehensive debugging capabilities.

### Missing Debuggers 🚨
- **WinDbg**: No MCP implementation (critical gap for Windows/kernel debugging)
- **OllyDbg**: Missing MCP server
- **Immunity Debugger**: No MCP integration
- **rr debugger**: Time-travel debugging without MCP support

## Static Analysis Tools

### Available
- **[YaraFlux](https://github.com/ThreatFlux/YaraFlux)**: YARA-based MCP server for malware detection and signature matching.

### Missing Static Analysis Tools 🚨
- **BinDiff**: No MCP server for binary diffing
- **angr**: Missing symbolic execution framework integration
- **Triton**: No dynamic symbolic execution support
- **Bindiff**: Binary comparison without MCP

## Dynamic Analysis Tools

### Available
- **[frida-mcp](https://github.com/dnakov/frida-mcp)**: MCP server for Frida with process management, script injection, and real-time instrumentation.

### Missing Dynamic Analysis Tools 🚨
- **Intel Pin**: No MCP server for dynamic binary instrumentation
- **DynamoRIO**: Missing MCP integration for code coverage analysis
- **API Monitor**: No MCP support for Windows API monitoring
- **Process Monitor**: Missing MCP server
- **Detours**: No MCP integration for Windows API hooking

## Network Analysis

### Excellent Coverage
- **[WireMCP](https://github.com/0xKoda/WireMCP)**: Wireshark MCP server with threat detection capabilities.
- **[Burp Suite MCP](https://github.com/PortSwigger/mcp-server)**: Official PortSwigger implementation.
- **[BurpMCP](https://github.com/swgee/BurpMCP)**: Community extension for enhanced security testing.
- **[ZAP-MCP](https://github.com/ajtazer/ZAP-MCP)**: OWASP ZAP integration with SQLMap support.

### Missing Network Tools
- **Fiddler**: No MCP server for HTTP debugging
- **mitmproxy**: Missing MCP integration

## Android/Mobile RE Tools

### Available
- **[Jadx MCP Plugin](https://github.com/mobilehackinglab/Jadx-MCP-Plugin)**: Decompiling Android apps with AI assistance.
- **[jadx-mcp-server](https://github.com/zinja-coder/jadx-mcp-server)**: Alternative JADX integration.
- **[apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server)**: APK manipulation and analysis (part of Android RE MCP Suites).
- **Frida**: Available via frida-mcp for mobile dynamic analysis.

### Missing Mobile Tools 🚨
- **dex2jar**: No MCP server for DEX to JAR conversion
- **objection**: Missing Frida-based mobile testing integration
- **MobSF**: No MCP support for Mobile Security Framework
- **APK Analyzer**: Missing Android Studio integration
- **Androguard**: No MCP server for Python-based Android analysis

## Security Testing Tools

### Available
- **[mcp-for-security](https://github.com/cyproxio/mcp-for-security)**: Collection including SQLMap, FFUF, NMAP, Masscan and more.
- **Multiple Burp Suite implementations**: See Network Analysis section.
- **OWASP ZAP**: Multiple MCP servers available.

## Missing Categories (Need Community Help!) 🚨

The following categories represent significant opportunities for community contribution. These tools are essential to reverse engineering workflows but currently lack MCP integration:

### Packers/Unpackers
- **UPX**: Universal Packer - **NO MCP SERVER**
- **PEiD**: Packer identifier - **NO MCP SERVER**
- **Detect It Easy**: Signature-based packer detection - **NO MCP SERVER**
- **ExeinfoPE**: Executable analyzer - **NO MCP SERVER**

### Malware Analysis Platforms
- **MalCat**: Dynamic malware analysis - **NO MCP SERVER**
- **Cuckoo Sandbox**: Dynamic malware analysis - **NO MCP SERVER**
- **CAPE**: Configuration and Payload Extraction - **NO MCP SERVER**
- **Joe Sandbox**: Commercial malware analysis - **NO MCP SERVER**
- **ANY.RUN**: Interactive malware analysis - **NO MCP SERVER**
- **pestudio**: Static malware analysis - **NO MCP SERVER**

### Fuzzing Tools
- **AFL++**: Advanced fuzzing framework - **NO MCP SERVER**
- **libFuzzer**: LLVM fuzzing library - **NO MCP SERVER**
- **honggfuzz**: Security-oriented fuzzer - **NO MCP SERVER**
- **Radamsa**: Test case generator - **NO MCP SERVER**

### File Format Analysis
- **ExifTool**: Metadata extraction - **NO MCP SERVER**
- **Foremost**: File carving - **NO MCP SERVER**
- **binwalk**: Firmware analysis - **NO MCP SERVER**

## Presentations and Tutorials

- **[Automated AI Reverse Engineering with MCP for IDA and Ghidra](https://www.youtube.com/watch?v=iFxNuk3kxhk)**: Live demonstration of MCP plugins with practical examples.
- **[Using an MCP Server with IDA and VS Code / Roo Code for Vulnerability Research](https://www.youtube.com/watch?v=ZFABxmJTm6Y)**: Comprehensive vulnerability research workflow.
- **[Setting up IDA Pro MCP server for AI assisted reverse engineering](https://www.youtube.com/watch?v=2z4LXyHX6KA)**: Step-by-step installation and configuration guide.
- **[Supercharging Ghidra: Using Local LLMs with GhidraMCP via Ollama and OpenWeb-UI](https://medium.com/@clearbluejar/supercharging-ghidra-using-local-llms-with-ghidramcp-via-ollama-and-openweb-ui-794cef02ecf7)**: Guide for local AI integration.

## Getting Started with MCP Development

Want to create an MCP server for a missing tool? Here are resources to get started:

### Learning Resources
- **[Microsoft MCP for Beginners](https://github.com/microsoft/mcp-for-beginners)**: Comprehensive curriculum with examples in multiple languages.
- **[MCP Dev Days](https://developer.microsoft.com/en-us/reactor/series/S-1563/)**: Microsoft's official MCP conference and learning resources.
- **[MCP Specification](https://modelcontextprotocol.io/)**: Official protocol documentation.

### Development Patterns
Most successful RE tool MCP servers follow these patterns:
- **Plugin + Bridge Architecture**: GUI tools use a plugin that bridges to an external MCP server
- **SSE (Server-Sent Events)**: Preferred transport for real-time integration
- **Headless Variants**: Automation-focused servers for CI/CD workflows
- **Security-First**: OAuth 2.1, encrypted communication, and sandboxed execution

### Example Minimal Implementation
Check out the simplest implementations in each category:
- **IDA Pro**: `mrexodia/ida-pro-mcp` - Clean, well-documented architecture
- **Ghidra**: `suidpit/ghidra-mcp` - Straightforward Java implementation  
- **Static Analysis**: `ThreatFlux/YaraFlux` - Simple YARA integration

### Priority Development Areas
Based on community needs assessment:
1. **Fuzzing Tools**: AFL++ integration would enable AI-guided fuzzing
2. **Windows Debugging**: WinDbg MCP would complete debugger ecosystem
3. **Malware Sandboxes**: Cuckoo/CAPE integration for automated analysis

## Community & Events

### Recent Developments
- **[World's Biggest MCP Hackathon](https://biggest-mcp-hackathon.devpost.com/)**: May 2025 event with $10K+ prizes
- **[HuggingFace Agents-MCP Hackathon](https://huggingface.co/Agents-MCP-Hackathon)**: 4,100+ participants, $16.5K prizes
- **MCP Dev Days**: Microsoft's July 2025 virtual conference


### Follow Development
- **Twitter**: Share your MCP servers with @EdwardCrowderX
- **Awesome Lists**: [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers), [awesome-mcp-security](https://github.com/Puliczek/awesome-mcp-security)
- **Community Hubs**: [PulseMCP](https://www.pulsemcp.com/), [Glama MCP](https://glama.ai/mcp/servers)

## Contributing

We welcome contributions! Here's how you can help:

### Add New Tools
1. **Found an MCP server we missed?** Open a PR with the tool details
2. **Created your own MCP server?** We'd love to feature it!
3. **Know of tools that need MCP servers?** Add them to the "Missing" sections

### Improve Existing Entries
- Add implementation details (language, transport method, key features)
- Update status information (experimental, active, production-ready)
- Include links to documentation, tutorials, or demo videos

### Create MCP Servers
Priority areas needing development:
- **Packers/Unpackers** (UPX, PEiD, DIE)
- **Fuzzing Tools** (AFL++, libFuzzer, honggfuzz)
- **Windows Debugging** (WinDbg)
- **Malware Analysis** (Cuckoo, CAPE)

### Quality Guidelines
When submitting entries, please include:
- Brief description of the tool's purpose
- Key features and capabilities
- Implementation status (experimental/active/production)
- Primary transport method (SSE/STDIO/HTTP)
- Compatible clients (Claude Desktop, Cursor, VSCode, etc.)

## License

This list is released under the MIT license.

---

**Legend**: ⭐ = Well-established with multiple implementations | 🚨 = Critical gap needing community contribution
