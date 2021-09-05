# Rust Programming tutorial: first steps

```
$ sudo apt install build-essential
$ sudo apt-get update

$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh

 .$ $HOME/.cargo/env

$ rustup update

$ cargo new tutorial
$ cd tutorial

$ cat Cargo.toml
[package]
name = "tutorial"
version = "0.1.0"
edition = "2018"
authors = ["Kenton Troy Davis <kdavis@cloudera.com>"]
# See more keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html
[dependencies]

$ vi src/main.rs
$ cargo check
$ cargo build
$ cargo run

```
