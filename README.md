# Chief Homebrew Tap

Homebrew casks for Chief's command-line tools. macOS only.

## Install

```sh
brew install --cask Storytell-ai/tap/chief
brew install --cask Storytell-ai/tap/chief-mcp
```

`Storytell-ai/tap` resolves to this repository (`Storytell-ai/homebrew-tap`). Or tap once, then install by name:

```sh
brew tap Storytell-ai/tap
brew install --cask chief
brew install --cask chief-mcp
```

## Casks

| Cask | Source | Description |
|------|--------|-------------|
| `chief` | [Storytell-ai/chief-cli](https://github.com/Storytell-ai/chief-cli) | Chief command-line interface |
| `chief-mcp` | [Storytell-ai/chief-mcp](https://github.com/Storytell-ai/chief-mcp) | Chief MCP server |

The binaries are unsigned; the casks strip the `com.apple.quarantine` attribute on install so they run without a Gatekeeper prompt.

## Maintenance

Casks in [`Casks/`](Casks) are generated and pushed by GoReleaser when a source repo cuts a release; they aren't edited here by hand.
