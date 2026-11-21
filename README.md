# SigmaOS-webcam

Webcam management (V4L2 discovery, capture, camera control)

- **Category:** Desktop
- **Engine:** webcam
- **Tier:** 2
- **Language:** Rust
- **Provides:** sigmawebcam

Part of the [SigmaOS](https://github.com/AaryanSinghChauhan09/SigmaOS)
multi-repository component ecosystem.

## Build & Test

```sh
cargo build
cargo test
```

## Contract

This component declares its interface in `COMPONENT.toml`:

- `provides` — capabilities other components may depend on
- `depends_on` — component names this component requires

## License

Apache-2.0 — see [LICENSE](LICENSE).
