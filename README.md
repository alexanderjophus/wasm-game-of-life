# WASM Game of Life

This is a simple implementation of Conway's Game of Life using Rust and WebAssembly.

It's not original work. I'm just working through the tutorial at https://rustwasm.github.io/docs/book/

## Hacking

Note: needs to use Rust 1.81, there seems to be an issue with wasm-pack and Rust 1.82+

```bash
wasm-pack build
```

This should create a `pkg` directory with the compiled wasm module.

Then you can run the web server with:

```bash
cd www
npm install
npm run start
```
