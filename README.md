# BitsRun Homebrew tap

Install `bitsrun`, the command line and terminal coding agent for [BitsRun](https://bitsrun.com): run open models from Ollama or
Hugging Face as private, OpenAI-compatible APIs that sleep when idle and bill per second.

```sh
brew tap bitsrun/tap
brew trust bitsrun/tap
brew install bitsrun
```

Homebrew asks you to trust a tap once before it installs from it; this tap holds only `bitsrun`. Update with `brew upgrade bitsrun`. Works on macOS (Apple Silicon and Intel)
and Linux (ARM and x86-64).

This repository holds only the Homebrew formula. It installs the same signed, notarized binaries as
`curl -fsSL https://get.bitsrun.com | sh`, pinned by SHA-256 to a release whose checksum file carries the BitsRun release signature.
The formula is regenerated on every release. `bitsrun` is free to use and closed source.

- Install options and docs: https://bitsrun.com/install/ and https://bitsrun.com/docs/cli/
- Help: support@bitsrun.com
