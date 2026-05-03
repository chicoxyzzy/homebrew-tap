# homebrew-tap

Homebrew tap for [chicoxyzzy](https://github.com/chicoxyzzy) projects.

## Available formulae

| Formula | Source | Install |
|---|---|---|
| `hecate` | [chicoxyzzy/hecate](https://github.com/chicoxyzzy/hecate) | `brew install chicoxyzzy/tap/hecate` |

## How it works

This tap is auto-maintained. Each Hecate release pushes an updated
`Formula/hecate.rb` here from goreleaser, pinning the new version's
darwin/linux × amd64/arm64 download URLs and SHA-256s.

## Troubleshooting

```bash
# Re-sync the tap
brew update

# Inspect what's installed
brew info chicoxyzzy/tap/hecate

# Uninstall
brew uninstall hecate
brew untap chicoxyzzy/tap
```
