## Image Processor

This is an image processing application. It simply shrinks an image to half its size.

It is built using Rust + Wasm (wasm-pack)

### Requirements
- [Wasm-pack](https://rustwasm.github.io/wasm-pack/installer/)
- [Nodejs](https://nodejs.org)

### Usage
```bash
    cd image-processor

    # build the rust project
    cargo build

    # build wasm
    wasm-pack build

    # move into client project
    cd client

    # install packages
    npm install

    # start the UI
    npm run start
```

