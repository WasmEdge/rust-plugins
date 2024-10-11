# WASI NN Burn

A plugin compatible with the wasi_nn proposal, using burn.rs framework as the backend.

Currently, two models have been integrated: SqueezeNet and Whisper. 

The command to compile the plugin is as follows.

```bash
cargo build --features=squeezenet -p wasi_nn_burnrs

or

cargo build --features=whisper -p wasi_nn_burnrs
```