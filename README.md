# cargo-template-test-submodule

A test cargo-template for testing cargo template with git submodules.

### Warning

To test this, you must use a Nighly version of Rust.

```bash
rustup install nightly
# OR, if you already have a nightly version
rustup update nightly
```

*Do not forget to override the default toolchain*

### How to use it ?

1. Install [cargo-generate](https://github.com/ashleygwilliams/cargo-generate):

```sh
cargo install cargo-generate
```

2. Clone this application, which is a fork of [rocket-base](https://github.com/k0pernicus/cargo-template-rocket-base):

```sh
cargo generate --git https://github.com/k0pernicus/cargo-template-test-submodule --name test-submodule
```

3. Check if the internal `cargo-generate-submodule` directory contains at least a README.md file.  
If not, this test failed :(
