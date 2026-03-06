# rust-buildpack

Build and install rust HTTP server application.

## How it works

Expect a `Cargo.toml` in the root directory, and source files in `src` directory ([Cargo project structure](https://doc.rust-lang.org/book/ch01-03-hello-cargo.html)).
Build an optimized executable and install it in the build directory’s `bin/` directory.

The server application must listen on any hosts (`0.0.0.0`) and port from the environment variable `PORT`.
