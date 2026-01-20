# Interfacer (WIP)

A small Bash CLI tool to list network interfaces and run quick actions like enabling/disabling an interface.  
This script is **unfinished** and currently focuses on basic interface selection + a simple loader animation for commands.

## Features (current)
- Lists interfaces from `ip -br a`
- Lets you select an interface by number
- Menu actions:
  - Enable interface (brings link up)
  - Disable interface (brings link down)
  - Managed Mode (placeholder)
  - Monitor Mode (placeholder)
- Sudo check (prompts once if needed)
- Loader animation while a command runs

## Requirements
- Linux
- `ip` (from `iproute2`)
- `awk`
- `sudo`
- Bash

## Usage
Make it executable:
```bash
chmod +x Interfacer
