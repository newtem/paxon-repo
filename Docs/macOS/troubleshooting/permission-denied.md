# Troubleshooting: `Permission denied` on macOS when running `paxon`

## Issue Description
When running the `paxon` command on macOS (Terminal, iTerm2, kitty, etc.), the application fails with a permission error such as:

```bash
zsh: permission denied: paxon
```

## Solutions
+ Run with sudo (Recommended)
+ Add execute permission
`chmod +x paxon`