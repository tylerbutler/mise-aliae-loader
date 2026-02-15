# aliae-loader

A cross-platform mise plugin that automatically loads `.aliae.toml`
alias files when a directory is activated via `.tool-versions`.

## Installation

```sh
mise plugin install aliae-loader https://github.com/YOUR_USERNAME/mise-aliae-loader
```

## Usage

Add a `.aliae.toml` file to any directory. When mise activates that directory,
the plugin will automatically run `aliae load .aliae.toml` to apply the aliases.

## Requirements

- [mise](https://mise.jdx.dev/)
- [aliae](https://github.com/JanDeDobbeleer/aliae) installed and available in PATH
