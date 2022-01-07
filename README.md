# NEAR-Labyrinth Rust Contract

## Getting started

To get started:

**src/lib.rs** is the main contract file

Test the contract

    `cargo test -- --nocapture`

Build the contract

    `RUSTFLAGS='-C link-arg=-s' cargo build --target wasm32-unknown-unknown --release`

