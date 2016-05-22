[fisherman]: https://github.com/fisherman/fisherman

# [fisherman] brew tap

[![](https://img.shields.io/badge/fisherman-2.7.9-blue.svg)](https://github.com/fish-shell/fish-shell/releases/tag/2.3b2)
[![](https://img.shields.io/badge/license-MIT-blue.svg)](https://tldrlegal.com/license/mit-license)
[![](https://fisherman-wharf.herokuapp.com/badge.svg)](https://fisherman-wharf.herokuapp.com)

## Usage

```shell
brew tap fisherman/tap
```

Then choose to install:

* the lastest stable version of [fisherman]

  ```
  brew install fisherman
  ```

* or latest commits from the `master` branch

  ```
  brew install --HEAD fisherman
  ```

When you `brew update` this tap will be automatically updated, then you can upgrade fisherman as any other formula:

```shell
brew update
brew upgrade fisherman
```

## Maintaining

Update the two fields in [`fisherman.rb`](./fisherman.rb#L5-L6):

- `url` the version in `fisher.fish`
- `sha256` which can be obtained with `shasum -a 256 fisher.fish`
