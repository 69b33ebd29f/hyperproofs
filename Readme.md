# Hyperproofs

Hyperproofs, the first vector commitment (VC) scheme that is efficiently maintainable and aggregatable.
This repo contains the implementation of Hyperproofs in go.

This repo depends on:
- [mcl-wrapper](https://github.com/69b33ebd29f/mcl-wrapper/) for elliptic curve operations.
- [kzg-hyper](https://github.com/69b33ebd29f/kzg-hyper) for KZG commitments.
- [gipa-hyper](https://github.com/69b33ebd29f/gipa-hyper) for proof aggregation.


## Instructions

0. Run ```time bash scripts/hyper-go.sh``` to setup PRK, VRK, UPK, etc.
1. Run ```time bash scripts/hyper-test.sh``` to run the test cases.
2. Run ```time bash scripts/hyper-bench.sh``` to replicate the benchmarks reported in the paper.
