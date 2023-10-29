# Homework 7

## Noir

### Questions

Follow the instructions to install Rust and Noir ( the nargo directory is in crates/nargo)

- 1). Create an example project
- 2). Create a new project
```
nargo new hello_world
```
- 3). Build the project

```
cd hello_world
nargo check
```
- 4). Edit the inputs in the Prover.toml file
```
x = "1" y = "2"
```
- 5). Generate the proof
```
nargo prove
```

- 6). Verify the proof

```
nargo verify
```

No output from the verifier signals success, if the
proof fails to verify it will produce an error.


### Answers

 ../code/noir/hello_world/proofs/hello_world.proof

