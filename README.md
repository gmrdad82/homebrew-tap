# homebrew-tap

[![CI](https://github.com/gmrdad82/homebrew-tap/actions/workflows/ci.yml/badge.svg)](https://github.com/gmrdad82/homebrew-tap/actions/workflows/ci.yml)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-ff69b4?logo=githubsponsors)](https://github.com/sponsors/gmrdad82)

Homebrew formulas for [gmrdad82](https://github.com/gmrdad82) tools — macOS
(Intel and Apple Silicon) and Linux alike. Managed by goreleaser: formulas
update automatically with each release, nothing here is edited by hand.

```sh
brew install gmrdad82/tap/pito-tui
```

Or in two steps, if you like your taps explicit:

```sh
brew tap gmrdad82/tap
brew install pito-tui
```

## What lives here

- [**`pito-tui`**](https://github.com/gmrdad82/pito-tui) — the terminal
  client for [PITO](https://github.com/gmrdad82/pito), the self-hosted,
  chat-first YouTube channel manager. See the whole family at
  [pitomd.com](https://pitomd.com): the server, the
  [Android app](https://github.com/gmrdad82/pito-android), and the TUI.

## How it works

`pito-tui`'s release pipeline (goreleaser, tag-driven) pushes an updated
`Formula/pito-tui.rb` here on every release. CI lints whatever lands
(`ruby -c` + `brew style`); humans only ever touch the README and the
plumbing.

## License

[AGPL-3.0](LICENSE), same as the whole PITO family.
