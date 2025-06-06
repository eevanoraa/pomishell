# POMISHELL

This is a basic shell I wrote in Rust for fun. It supports a few built-in commands and can execute external programs.

## Features

- Command execution with arguments
- Built-in commands like `cat`, `ls`, `cd` and external commands
- Minimal error handling
- Basic command parsing

## TODO

- Input/Output Redirection
- Piping
- Command history
- More built-in commands
- Autocompletion (Tab)

## Building

Requires [Rust](https://www.rust-lang.org/tools/install). Clone the repository and run:

```bash
cargo build --release
```

The binary will be in `target/release/`.

## Usage

Run the shell:

```bash
cargo run
```

Or, after building:

```bash
./target/release/rust-shell
```

Type commands and press enter. Use `exit` to quit.
