# hello_rust

### How to install Rust?

Watch video
https://www.youtube.com/watch?v=rQ_J9WH6CGk&t=2455s

Steps:
* Go to Rust website https://www.rust-lang.org/tools/install
* Execute

`curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`

It will return following text

```
Welcome to Rust!

This will download and install the official compiler for the Rust
programming language, and its package manager, Cargo.

Rustup metadata and toolchains will be installed into the Rustup
home directory, located at:

  /home/ivan/.rustup

This can be modified with the RUSTUP_HOME environment variable.

The Cargo home directory is located at:

  /home/ivan/.cargo

This can be modified with the CARGO_HOME environment variable.

The cargo, rustc, rustup and other commands will be added to
Cargo's bin directory, located at:

  /home/ivan/.cargo/bin

This path will then be added to your PATH environment variable by
modifying the profile files located at:

  /home/ivan/.profile
  /home/ivan/.bashrc

You can uninstall at any time with rustup self uninstall and
these changes will be reverted.

Current installation options:


   default host triple: x86_64-unknown-linux-gnu
     default toolchain: stable (default)
               profile: default
  modify PATH variable: yes

1) Proceed with standard installation (default - just press enter)
2) Customize installation
3) Cancel installation

```
