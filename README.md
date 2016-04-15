# pythonvm-rust

[![Build Status](https://travis-ci.org/ProgVal/pythonvm-rust.svg?branch=master)](https://travis-ci.org/ProgVal/pythonvm-rust)

A Python virtual machine, written in Rust.

## Features

* prints strings to stdout
* useable as a library
* a fine-grained sandbox

## Try it

1. Install Python 3.4 (used as a parser and bytecode compiler), git, [Rust](https://www.rust-lang.org/downloads.html) and [Cargo](https://crates.io/install)
2. `git clone https://github.com/ProgVal/pythonvm-rust.git`
3. `cd pythonvm-rust`
4. `python3 -m compileall -b pythonlib examples`
5. `cargo run pythonlib/ examples/helloworld.pyc`