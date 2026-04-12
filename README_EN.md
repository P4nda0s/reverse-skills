English | [中文](README.md)

# Reverse Engineering Skills

Reverse engineering analysis skills, supporting 40+ AI coding agents.

**Designed to work with [IDA-NO-MCP](https://github.com/P4nda0s/IDA-NO-MCP)** - Export IDA decompilation results, then analyze with your AI coding agent.

## Skills Included

| Skill | Description |
|-------|-------------|
| `rev-symbol` | Analyze function symbols from exports/imports or decompiled code |
| `rev-struct` | Reconstruct data structures from decompiled functions |
| `rev-frida` | Generate Frida hook scripts using modern Frida API |
| `rev-unicorn-debug` | Debug specific code snippets using Unicorn emulator with environment simulation |
| `rev-dex-dumper` | Dump DEX files from a running Android app's memory for unpacking |

## Installation

```bash
npx skills add P4nda0s/reverse-skills
```

### Update & Remove

```bash
# Check for updates
npx skills check

# Update
npx skills update

# Remove
npx skills remove rev-symbol rev-struct
```

## License

MIT
