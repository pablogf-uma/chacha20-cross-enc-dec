<h1 align="center">ChaCha20 Crossed-End Encryption</h1>


- This program utilizes the implementation of the regular [chacha20](https://github.com/pablogf-uma) algorithm and its vectorized versions ([128](https://github.com/pablogf-uma/chacha20-128-vec) and [256](https://github.com/pablogf-uma/chacha20-256-vec)-bit respectively) to encrypt and decrypt a plaintext.

- For a given plaintext, each chacha20 implementation encrypts, and the other two decrypt.

- This demonstrates the correct functioning of the cryptosystem across its different vectorized and non-vectorized implementations.
