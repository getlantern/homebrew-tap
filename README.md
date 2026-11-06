# getlantern/homebrew-tap

Homebrew formulae for [Lantern](https://lantern.io) tools, on macOS and Linux.

## lamplighter

Run a Lantern node, which helps people in censored countries reach the open internet:

```bash
brew install getlantern/tap/lamplighter
brew services start lamplighter
```

See [lamplighter.lantern.io](https://lamplighter.lantern.io) for its options and how to manage it. The formula was called `lantern-box`. It stays here until lantern-box's installer uses the new name, and then `brew upgrade` will move installs of it to `lamplighter`, keeping the node's identity and flags.

The formulae here are published by each project's release, so don't edit them by hand.
