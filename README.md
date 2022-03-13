# ip_utilities

IP Utilities, split ranges, convert to/from decimal.  React+Rust

## Following

<https://www.joshfinnie.com/blog/using-webassembly-created-in-rust-for-fast-react-components/>

## Notes

```console
cargo build --target wasm32-unknown-unknown
wasm-bindgen target/wasm32-unknown-unknown/debug/ip_utilities.wasm --out-dir build
```
