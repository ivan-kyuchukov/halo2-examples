# Halo2 Examples

This repo includes a few simple examples to illustrate how to write circuit in Halo2.

## Instruction

Compile the repo

```
cargo build
```

Run examples
```
cargo test -- --nocapture test_example1
cargo test -- --nocapture test_example2
cargo test -- --nocapture test_example3

cargo test -- --nocapture test_mymip_v2
```

Plot the circuit layout
```

cargo test --all-features -- --nocapture plot_fibo1
cargo test --all-features -- --nocapture plot_fibo2

cargo test --all-features -- --nocapture test_merkle_v2
cargo test --all-features -- --nocapture plot_mymip_v2

```
