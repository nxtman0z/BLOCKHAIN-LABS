`# Lab 2 – SHA-256 in Action: Cryptographic Hashing

## Objective
Understand the working of the SHA-256 hashing algorithm and observe how data changes affect the resulting hash.

## Steps
1. Visit the [SHA-256 Hash Generator](https://emn178.github.io/online-tools/sha256.html).
2. Enter different pieces of data into the input field.
3. Observe the generated SHA-256 hash for each input.
4. Make small changes to the data and note how the hash changes drastically (Avalanche Effect).
5. Test HMAC functionality with private keys for enhanced security.

## Observations
- Even a single character change produces a completely different hash.
- The SHA-256 algorithm produces a fixed 256-bit (64 hex characters) output.
- Hashing is **one-way**: you cannot retrieve the original data from the hash.
- The avalanche effect ensures high sensitivity and prevents pattern recognition.

## Tools Used
- **Website:** [SHA-256 Hash Generator](https://emn178.github.io/online-tools/sha256.html)
- **Browser:** Brave
- **OS:** Windows 11

## Final Output
A valid SHA-256 hash generated for the given input data, demonstrating cryptographic integrity and uniqueness.`
