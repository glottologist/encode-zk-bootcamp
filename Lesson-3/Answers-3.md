# Homework 3

## ZoKrates plugin in Remix

### Questions

- 1). Use the example file to generate a proof to show that a prover knows the square root of 25.

- 2). Try to create an invalid proof

- 3). Follow the example to build a proof that you know the pre image of a hash - https://zokrates.github.io/examples/sha256example.html

- 4). In principle how could you use Zokrates to verify that a
  certain address on Ethereum has more than say 1 ETH ?

### Answers

- 1). ./sqrt_proof/sqrt-proof.zok

- 2). The ZoKrates compiler will reject invalid proofs. We could try to mess with the proof but that would then be rejected by the verifier.

- 3). ./preimage-hash-proof/preimage-hash-proof.zok

- 4). The biggest challenge would be to ensure the off-chain proof system had up to date (and accurate) knowledge of the on-chain data.
