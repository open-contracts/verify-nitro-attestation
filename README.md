# verify-nitro-attestation
Towards fraud proofs of the attestation doc for the `Verifier.sol` contract in [Truebit](https://truebit.io). 

1) put the attestation doc into `data/attestation_doc` in binary format. 
2) `cargo run`
3) if verification suceeds, public key is extracted into `data/public_key.txt` and hash of the `.eif` is put into `data/pcr0.txt`
