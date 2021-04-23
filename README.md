# Rust GBA Template

This is a Rust template for GBA development. This is based on [mogenson/gba-game-of-life](https://github.com/mogenson/gba-game-of-life).

## Install dependencies

```sh
$ rustup install nightly # install nightly
$ rustup component add --toolchain=nightly rust-src # install rust sourcecode
$ brew install --cask gcc-arm-embedded # install arm toolchain
```

## Build

```sh
$ git clone https://github.com/pokemium/rust-gba-template
$ make build # > target/thumbv4-none-agb/release/gba-template
```

`target/thumbv4-none-agb/release/gba-template` is GBA ROM file. If you like, add `.gba` extension to ROM file.
