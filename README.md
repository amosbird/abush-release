# abush

A terminal-native, multi-agent coding workbench in Rust.

<p align="center">
<img src="https://img.shields.io/github/v/release/amosbird/abush-release?label=latest" alt="latest release">
<img src="https://img.shields.io/badge/platform-Linux%20%7C%20macOS%20%7C%20Windows-blue" alt="platforms">
</p>

Source code is not yet public. Open-source release is planned for 2026.

## Install

```bash
# Linux x86_64 (static binary):
curl -fsSL https://github.com/amosbird/abush-release/releases/latest/download/abush-linux-x86_64 -o abush
chmod +x abush && mv abush ~/.local/bin/

# macOS (universal binary, Apple Silicon + Intel):
curl -fsSL https://github.com/amosbird/abush-release/releases/latest/download/abush-macos-universal -o abush
chmod +x abush && mv abush ~/.local/bin/

# Windows x64 (PowerShell):
Invoke-WebRequest -Uri "https://github.com/amosbird/abush-release/releases/latest/download/abush-win-x86_64.exe" -OutFile abush.exe
Move-Item abush.exe "$env:LOCALAPPDATA\Microsoft\WindowsApps\"
```

## Update

```bash
abush update
```

## Verify

Each release includes `.sha256` checksums:

```bash
curl -fsSL https://github.com/amosbird/abush-release/releases/latest/download/abush-linux-x86_64.sha256
sha256sum abush
```
