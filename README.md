# Claude Plugins

Claude Code plugins by William Toth.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **bigdata** | FRC Big Data telemetry analysis. Ingest WPILog files, query robot data with SQL, browse schema registry. |

## Installation

### 1. Install the bigdata binary

Download from [GitHub Releases](https://github.com/willtoth/claude-plugins/releases/latest):

- **Linux x64:** `bigdata-x86_64-unknown-linux-musl`
- **Windows x64:** `bigdata-x86_64-pc-windows-msvc.exe`

Place on PATH:
- **Linux:** `~/.local/bin/bigdata` (run `chmod +x` after downloading)
- **Windows:** `%LOCALAPPDATA%\bigdata\bigdata.exe`

### 2. Add the marketplace

```
/plugin marketplace add willtoth/claude-plugins
```

### 3. Install the plugin

```
/plugin install bigdata@claude-plugins
```

### Verify

```bash
bigdata doctor
```
