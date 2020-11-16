# Quick Start Guide for Rust

## Learning Resources
Unlike other languages, we cannot learn Rust by directly jump into coding. 
This is the first con about the Rust language.
We need to understand few important concepts of Rust, before we start writing some code samples. Otherwise understanding the code snippets from code samples would quickly become frustating and boring. 
Few important resourses to start with:
* **The Rust Programming Language**
* **Rust By Example**
* **Rustlings**: The command line version of Rust Guide

## Tools required
* **RustUP**
* **Cargo**

### How to install Rust tool chain?
All you need to do is run the following command in any Nix OS; This will install tools like rust compiler and package manager

> ```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```

### How to check the tools
* Check the rust compiler

```
$ rustc
Usage: rustc [OPTIONS] INPUT

Options:
    -h, --help          Display this message

...

```

We generally dont use the compiler `ructc` directly; we use the package manager tool `cargo` to build, test, and release the rust projects

* Check Package manager **Cargo**

```
$ cargo
Rust's package manager

USAGE:
    cargo [+toolchain] [OPTIONS] [SUBCOMMAND]

OPTIONS
...
```

### How to update the Rust tool chain

```
$ rustup update
info: syncing channel updates for 'stable-x86_64-unknown-linux-gnu'
info: checking for self-updates

  stable-x86_64-unknown-linux-gnu unchanged - rustc 1.47.0 (18bf6b4f0 2020-10-07)

info: cleaning up downloads & tmp directories
```
