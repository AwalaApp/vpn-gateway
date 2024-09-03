# Awala VPN Gateway

This is the Awala VPN Gateway, a production-ready implementation of the
[gateway](https://github.com/relaycorp/fanqiang-poc/tree/main/gateway) in the
[Fān Qiáng Proof of Concept](https://github.com/relaycorp/fanqiang-poc).

## System dependencies

- Rust.
- [cargo-run-bin](https://github.com/dustinblackman/cargo-run-bin).

Set up:

```sh
cargo build
cargo bin --install
```

## Running Tests

```sh
cargo test-cov
```

## Licence

This project is licensed under the Business Source License. See the
[LICENSE](./LICENSE) file for more details.
